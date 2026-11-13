# Mavigator Indoor Digitizer

The tool we use to draw building interiors for Mavigator (CSE 3311, Team 7). A script already traced 48 buildings
from UTA's evacuation diagrams. Each trace is a **draft**: most rooms, doors, hallways and stairs are in place, and
a person has to check it against the diagrams and fix the rest. That review is this iteration's job.

**Open the tool:** https://antovu.github.io/mavigator-indoor-digitizer/ (Chrome or Edge on a computer).

## What you need

- **Your buildings' diagrams.** Anthony sends you a zip of the PDFs privately. They are UTA's copyrighted
  evacuation diagrams: keep them on your computer, and never commit, upload or post them (or screenshots of them).
- **The Mavigator repo** cloned, to hand in your work as a pull request.

## Reviewing a building

1. Open the tool. Under **Pick a building to review…**, choose one of yours.
2. Press **Load the auto trace for this building** (in the Tools panel). If the building feels laggy, press
   **Simplify shapes (less lag)** next to it: it drops extra points along walls and outlines (Undo puts them back).
3. Press **Add folder…** and pick the folder you unzipped. Each floor's diagram appears under the trace, already lined
   up. Switch floors with the floor buttons.
4. Work through that building's list in [REVIEW.md](REVIEW.md), then compare each floor with its diagram:
   missing rooms, misread room numbers, doors in the wrong place, hallways that don't connect, stairs that skip a
   floor. **How this works** at the top of the tool explains each drawing tool. The **Checklist** panel lists what the
   tool itself finds wrong; aim to empty it.

   To straighten crooked walls, press **Square to angles…** (next to Simplify) once the diagram sits right. It turns
   walls to 0, 30, 45, 60 or 90° from the diagram. Rooms are always safe to square. Square hallways only after
   joining any hallway gaps (the dashed orange lines), and check the junction rings after. Undo puts everything back.

   Then press **Close wall gaps…**: rooms grow across the wall-thick gaps the script leaves, so neighbors meet in the
   middle and rooms reach the floor outline. It never crosses a hallway or a gap wider than its limit (0.6 m between
   rooms, 0.8 m to the outline). Best order: place the diagram, then Simplify, Square to angles, Close wall gaps, and
   fix the details last.

   **Tidy rooms…** (next to Close wall gaps) does most of a floor's cleanup in one press. Each room is rebuilt from
   its real walls, so door-swing teeth, notches and cut-off corners go. Walls a wall's thickness from a neighbor's,
   or near the outline, move onto one line. A room short of the next room in its row grows out to it, but never
   across a hallway, into another room or past the outline. Overlapping rooms are split. Rooms that are already
   clean rectangles stay put and lead: fix one room in a row by hand against the diagram, press Tidy, and the rest of
   the row lines up with it. Rooms with a long slanted wall or curves are left as drawn. Then check each floor
   against its diagram, because it lines rooms up with each other, not with the PDF.

   **Line up to a line** (beside Level to a wall) is for a row Tidy gets wrong. Click where a line starts and where
   it ends, along a hallway's edge or a row of rooms. Every room wall that runs along it, within the distance you set,
   moves onto it. Keep that distance under the hallway's width, or the rooms across the hallway move too. It stays on
   for the next line; Esc stops.

   **Doors into rooms…** (Tools panel) is for offices inside a suite: a room's door that opens into another room
   instead of a hallway, common after you add a room the script missed. It finds those doors on the whole floor or
   in a box you draw. It steps straight out from the wall each door sits on, and the first other numbered room
   within the distance you set is the room it connects to. It lists what it found and rings each door on the map;
   untick any that are wrong, then **Convert** turns them into doors between rooms. Doors farther than the distance
   from their own room's wall are skipped, as are rooms already joined by a door between them. Undo puts them back.

   **Snap doors to their room…** (Tools panel) moves each room door onto the nearest wall of its own room (a door
   between rooms onto the nearer wall of its two rooms, sides and all), on the whole floor or in a box you draw. Doors farther than the distance you set (1.5 m to start) are left alone and
   listed, as are doors whose room has no outline. Undo puts them back.

   **Boxify rooms…** (Tools panel) turns each room with more than 4 corners into a box: its 4 best corners, with
   the walls extended to meet where a corner was cut (a room traced around a pillar). **Whole floor** skips rooms
   whose box would be over 20% bigger, likely real L shapes, and lists them; **Box an area** changes every room
   whose middle is in the box, so drag over one of those to force it. Curved rooms and solids are left alone.
   Undo puts them back.
   An **Entrance** on a room's own outside wall (an office or lab door to the outdoors, no hallway within 3 m)
   leads into that room: routes reach it through the room's doors, and take it only when nothing else gets
   there. No hallway through the room is needed. Tick **Emergency exit** for an alarmed door instead.
   Some buildings join others inside (Science Hall into the Chemistry & Physics Building on floor 3, Trimble and
   Hammond, Preston, Carlisle and Ransom). Place an **Entrance** at that doorway and set **Leads to** the other
   building and the floor it opens onto there, which can be any floor. It only has to be in one of the two
   buildings, and the other building needs a hallway reaching that spot.
5. Press **Save this building**. It downloads `<building>.json` (for example `SH.json`).
6. In the Mavigator repo, all your buildings go on one branch of your own, one commit per building named after it.
   The first time:
   ```sh
   git switch main && git pull
   git switch -c review-josue
   ```
   Then after each building:
   ```sh
   # copy SH.json into indoor-reviews/
   git add indoor-reviews/SH.json
   git commit -m "Science Hall"
   git push -u origin review-josue
   ```
   After your first building, open a **draft** pull request into `main` and keep pushing to it. Mark it ready when
   all your buildings are in. To fix a building again, save it again, copy it over the old file, and commit it as
   "Science Hall: fix floor 2 stairs".

Your draft stays in your browser between visits (don't clear site data). To be safe, press **Save this building**
whenever you stop for the day.

## Who reviews what (proposal)

| Person | Buildings |
|---|---|
| Josue | SWSH, Vandergriff Hall, College Park Center, CAPPA, Science Hall, Central Library, PE, ELB, Ransom Hall, Studio Arts Center, Wetsel, ARDRC, CELB |
| Abiy | Life Science, Pickard Hall, University Center, COBA, MAC, Woolf Hall, University Hall, CPB, Nanotech, Carlisle Hall, EES, ARB, Preston Hall, EHS, LCD |
| Ayesha | Fine Arts, SEIR, West Hall, Trinity Hall, UAB, The Heights on Pecan, CRB, Hammond Hall, Swift Center, College Hall, Health Center, Texas Hall, Kalpana Chawla Hall |
| Anthony | Arlington Hall, Trimble Hall, Dan Dipert Welcome Center, UTA Police, GACB (these need map outline or walkway fixes too), The Lofts, Thermal Energy Plant (no rooms found: trace by hand) |

Nedderman Hall and ERB were traced by hand and are already in the app; leave them alone.

## Updating this site (Anthony)

From the Mavigator repo root: `python "Claude outputs/indoor-digitizer/build-site.py"` rebuilds `index.html`,
`campus-base.json`, `auto/` and `REVIEW.md` here. Then commit and push this repo.

Building outlines and walkways © OpenStreetMap contributors, ODbL.
