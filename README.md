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
2. Press **Load the auto trace for this building** (in the Save panel).
3. Press **Add folder…** and pick the folder you unzipped. Each floor's diagram appears under the trace, already lined
   up. Switch floors with the floor buttons.
4. Work through that building's list in [REVIEW.md](REVIEW.md), then compare each floor with its diagram:
   missing rooms, misread room numbers, doors in the wrong place, hallways that don't connect, stairs that skip a
   floor. **How this works** at the top of the tool explains each drawing tool. The **Checklist** panel lists what the
   tool itself finds wrong; aim to empty it.
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
