# Indoor maps: review list

The script traced these buildings from UTA's evacuation diagrams. Each one is a draft: most rooms, doors, room numbers, hallways and stairs are placed, and a person has to fix the rest. Nedderman Hall and ERB are already traced by hand and in the app, so they aren't listed.

**How to review a building:** open it in the Indoor Digitizer (Anthony shares the file and the tool), work through its list below, and compare each floor against its evacuation diagram. Then send Anthony the saved `indoor-edits.json`. Fix what the list names first; anything else you spot is a bonus.

**Columns:** *Fit* is how well the stacked floors line up with the building's outline on the map (0.85 or higher is good). *Routed* is how many room doors the app can route to from outside.

| Building | Code | Floors | Rooms | Fit | Routed | Status |
|---|---|---|---|---|---|---|
| Business Building | COBA | 1 2 3 4 5 6 | 322 | 0.9 | 358/358 | Good |
| Central Library | LIBR | B 1 2 3 4 5 6 | 160 | 0.96 | 199/199 | Good |
| Chemistry & Physics Building | CPB | 1 2 3 | 151 | 0.93 | 174/174 | Good |
| Chemistry Research Building | CRB | B 1 2 3 | 155 | 0.93 | 110/110 | Good |
| Earth and Environmental Sciences | EES | 1 2 | 124 | 0.93 | 131/131 | Good |
| Engineering Lab Building | ELB | 1 2 3 | 134 | 0.98 | 174/174 | Good |
| Health Center | - | B 1 | 34 | 0.95 | 25/25 | Good |
| Library Collections Depository | LCD | 1 | 17 | 0.98 | 11/11 | Good |
| Nanotech Building | NANO | 1 2 | 57 | 0.97 | 92/92 | Good |
| Preston Hall | PH | 1 2 3 | 47 | 0.91 | 55/55 | Good |
| Ransom Hall | RH | 1 2 3 | 106 | 0.96 | 104/104 | Good |
| University Hall | UH | 0 1 2 3 4 5 | 275 | 0.92 | 312/312 | Good |
| Wetsel Building | - | 1 2 | 108 | 0.98 | 116/116 | Good |
| Woolf Hall | WH | 1 2 3 4 | 196 | 0.96 | 258/258 | Good |
| Aerodynamics Research Building | ARB | 1 | 17 | 0.78 | 18/18 | Needs fixes |
| Amphibian and Reptile Diversity Research Center | ARDRC | 1 | 28 | 0.41 | 34/34 | Needs fixes |
| Arlington Hall | - | 1 2 3 | 173 | 0.9 | 329/365 | Needs fixes |
| CAPPA Building | CAPPA | 1 2 3 4 | 154 | 0.85 | 162/162 | Needs fixes |
| Carlisle Hall | CAH | 1 2 3 | 47 | 0.78 | 21/21 | Needs fixes |
| Civil Engineering Laboratory Building | CELB | 1 | 44 | 0.83 | 49/49 | Needs fixes |
| College Hall | CH | B 1 | 45 | 0.92 | 51/51 | Needs fixes |
| College Park Center | - | 0 1 2 | 149 | 0.85 | 179/179 | Needs fixes |
| Dan Dipert Welcome Center | - | 1 | 12 | 0.42 | 9/9 | Needs fixes |
| Environmental Health and Safety | EHS | 1 | 22 | 0.76 | 23/23 | Needs fixes |
| Fine Arts Building | FA | 1 2 3 4 | 256 | 0.89 | 316/316 | Needs fixes |
| General Academic Classroom Building | GACB | 1 | 22 | 0.32 | 20/20 | Needs fixes |
| Hammond Hall | HH | 1 2 4 5 | 93 | 0.84 | 84/84 | Needs fixes |
| Life Science Building | LS | B 1 2 3 4 5 6 | 399 | 0.95 | 394/394 | Needs fixes |
| Maverick Activities Center | MAC | 1 2 | 107 | 0.94 | 99/99 | Needs fixes |
| Physical Education Building | PE | 1 2 3 | 49 | 0.97 | 47/47 | Needs fixes |
| Pickard Hall | PKH | 1 2 3 4 5 6 | 246 | 0.9 | 280/280 | Needs fixes |
| SEIR Building | SEIR | B 1 3 4 | 215 | 0.85 | 186/186 | Needs fixes |
| SWSH - UTA School of Social Work & CONHI Smart Hospital | SWSH | B 1 2 3 4 | 180 | 0.92 | 200/200 | Needs fixes |
| Science Hall | SH | B 1 2 3 4 | 256 | 0.88 | 285/285 | Needs fixes |
| Studio Arts Center | SAC | 1 | 42 | 0.69 | 64/64 | Needs fixes |
| Swift Center | - | 1 2 | 53 | 0.86 | 49/49 | Needs fixes |
| Texas Hall | TXH | B | 31 | 0.85 | 15/15 | Needs fixes |
| The Heights on Pecan | - | 1 2 3 4 | 142 | 0.98 | 264/264 | Needs fixes |
| Trimble Hall | TH | B 1 2 3 | 92 | 0.8 | 0/90 | Needs fixes |
| Trinity Hall | - | 1 2 3 | 67 | 0.9 | 51/51 | Needs fixes |
| UTA Police Department | - | 1 | 34 | 0.69 | 32/32 | Needs fixes |
| University Administration Building | UAB | B 1 2 3 4 | 186 | 0.8 | 196/196 | Needs fixes |
| University Center | UC | B 1 2 | 232 | 0.85 | 261/261 | Needs fixes |
| Vandergriff Hall | - | 1 2 3 4 | 165 | 0.83 | 96/96 | Needs fixes |
| West Hall | - | 1 2 3 4 | 304 | 0.92 | 222/222 | Needs fixes |
| Kalpana Chawla Hall | KC | 1 2 3 | 144 | 0.67 | 277/277 | Not usable |
| The Lofts | - | 2 3 4 | 18 | 0.47 | 0/0 | Not usable |
| Thermal Energy Plant | - | 1 2 | 8 | 0.25 | 0/0 | Not usable |

## Good: a quick review

### Business Building (COBA)

- [ ] Floor 2: 15 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2: hallways are in 2 pieces (170, 97 m): connect them, unless the floor really is split
- [ ] Floor 3: room numbers probably misread: 3501
- [ ] 8 stairs/elevators are on one floor only (Stairs x1, Stairs x3, Stairs x4, Stairs x5, Stairs x6, Stairs x10, Stairs x12, Elevator x1): add their other floors, or delete any that aren't stairs
- [ ] 3 stairs/elevators skip a floor (Elevator x2 [1 3 4 5 6], Elevator x3 [1 3 4 5 6], Elevator x4 [1 3 4 5 6]): add the missing stops

### Central Library (LIBR)

- [ ] Floor 1: 3 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 1: 9 of 39 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 1: room numbers probably misread: A373
- [ ] Floor 6: 9 of 44 rooms weren't traced (merged into the hallway): draw them
- [ ] 1 stairs/elevators skip a floor (Elevator x4 [2 4]): add the missing stops

### Chemistry & Physics Building (CPB)

- [ ] Floor 1: room numbers probably misread: 1208A
- [ ] Floor 2: 1 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2: hallways are in 2 pieces (251, 12 m): connect them, unless the floor really is split
- [ ] 11 stairs/elevators are on one floor only (Stairs x1, Stairs x3, Stairs x4, Stairs x5, Stairs x6, Stairs x7, Stairs x8, Stairs x9, Elevator x2, Elevator x4, Elevator x5): add their other floors, or delete any that aren't stairs

### Chemistry Research Building (CRB)

- [ ] Floor B: 11 of 20 rooms have no door: add doors to B05, B06, B07, B08, B08A, B09, B10, B11...
- [ ] Floor 1: hallways are in 2 pieces (69, 1 m): connect them, unless the floor really is split
- [ ] Floor 2: hallways are in 3 pieces (78, 10, 6 m): connect them, unless the floor really is split
- [ ] Floor 3: hallways are in 2 pieces (97, 6 m): connect them, unless the floor really is split
- [ ] 2 stairs/elevators are on one floor only (Stairs x4, Stairs 3): add their other floors, or delete any that aren't stairs

### Earth and Environmental Sciences (EES)

- [ ] Floor 1: room numbers probably misread: 888
- [ ] 1 stairs/elevators are on one floor only (Stairs x4): add their other floors, or delete any that aren't stairs

### Engineering Lab Building (ELB)

- [ ] Floor 1: room numbers probably misread: 1041
- [ ] Floor 3: room numbers probably misread: 1322A
- [ ] 2 stairs/elevators are on one floor only (Stairs x2, Stairs x3): add their other floors, or delete any that aren't stairs
- [ ] 2 stairs/elevators skip a floor (Stairs x1 [1 3], Stairs x6 [1 3]): add the missing stops

### Health Center

- [ ] Floor B can't be reached: no stairs or elevator connects it to the rest. Add the missing stairs.
- [ ] Floor B: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] 6 stairs/elevators are on one floor only (Stairs x1, Stairs x2, Stairs x3, Stairs x4, Elevator 1, Elevator x2): add their other floors, or delete any that aren't stairs

### Library Collections Depository (LCD)

- Nothing flagged. Spot-check it against the diagrams.

### Nanotech Building (NANO)

- [ ] Floor 1: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 1 piece 2: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 1: hallways are in 3 pieces (125, 90, 5 m): connect them, unless the floor really is split
- [ ] Floor 2: 1 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] 4 stairs/elevators are on one floor only (Stairs x1, Stairs x3, Stairs x4, Elevator x1): add their other floors, or delete any that aren't stairs

### Preston Hall (PH)

- Nothing flagged. Spot-check it against the diagrams.

### Ransom Hall (RH)

- [ ] Floor 1: room numbers probably misread: 1051
- [ ] Floor 2: room numbers probably misread: 2061
- [ ] Floor 3: 1 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 3: room numbers probably misread: 3061

### University Hall (UH)

- [ ] Floor 2: hallways are in 2 pieces (157, 1 m): connect them, unless the floor really is split
- [ ] 14 stairs/elevators are on one floor only (Stairs x1, Stairs x3, Stairs x5, Stairs x6, Stairs x7, Stairs x8, Stairs x9, Stairs x10, Stairs x11, Stairs x12, Stairs x14, Stairs x17, Elevator x1, Elevator x4): add their other floors, or delete any that aren't stairs
- [ ] 1 stairs/elevators skip a floor (Stairs x15 [0 2]): add the missing stops

### Wetsel Building

- [ ] Floor 2: room numbers probably misread: 2050
- [ ] 5 stairs/elevators are on one floor only (Stairs x2, Stairs x3, Stairs x5, Elevator x1, Elevator x3): add their other floors, or delete any that aren't stairs

### Woolf Hall (WH)

- [ ] Floor 1: hallways are in 2 pieces (139, 1 m): connect them, unless the floor really is split
- [ ] Floor 3: room numbers probably misread: 3233
- [ ] Floor 4: room numbers probably misread: 4200
- [ ] 2 stairs/elevators are on one floor only (Stairs x1, Stairs x4): add their other floors, or delete any that aren't stairs
- [ ] 1 stairs/elevators skip a floor (Stairs x6 [1 4]): add the missing stops

## Needs fixes

### Aerodynamics Research Building (ARB)

- **Note:** The diagrams cover only the main building, not the small annex.
- [ ] Floor 1: hallways are in 2 pieces (46, 17 m): connect them, unless the floor really is split

### Amphibian and Reptile Diversity Research Center (ARDRC)

- **Note:** Only some of the diagrams are still archived, so parts of the building are missing.

### Arlington Hall

- **Note:** About half the rooms on each floor merged into the hallway: draw them. On floors 1 and 3 the east wing corridor has a gap between rooms 131 and 138 (333-348 on floor 3): draw it, and suites 133-148 route.
- Only 329 of 365 room doors can be reached from outside: check the entrances and that the hallways connect.
- [ ] Floor 1: hallways are in 11 pieces (275, 184, 88, 20, 19, 19, 18, 17, 15, 11, 7 m): connect them, unless the floor really is split
- [ ] Floor 2: 11 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2: hallways are in 10 pieces (704, 22, 19, 18, 18, 17, 17, 15, 15, 8 m): connect them, unless the floor really is split
- [ ] Floor 3: hallways are in 9 pieces (448, 88, 22, 19, 19, 18, 17, 15, 7 m): connect them, unless the floor really is split
- [ ] 5 stairs/elevators are on one floor only (Stairs x2, Stairs x4, Stairs x5, Stairs x6, Stairs x10): add their other floors, or delete any that aren't stairs
- [ ] 1 stairs/elevators skip a floor (Stairs x9 [1 3]): add the missing stops

### CAPPA Building (CAPPA)

- **Note:** Check the small corner stairwells on floor 3.
- [ ] Floor 1: hallways are in 5 pieces (341, 4, 3, 3, 3 m): connect them, unless the floor really is split
- [ ] Floor 1: room numbers probably misread: 1031
- [ ] Floor 2: 5 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2: 7 of 32 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 3: hallways are in 2 pieces (102, 56 m): connect them, unless the floor really is split
- [ ] 13 stairs/elevators are on one floor only (Stairs x1, Stairs x3, Stairs x6, Stairs x7, Stairs x8, Stairs x9, Stairs 3, Stairs x12, Stairs x13, Stairs x14, Elevator x1, Elevator x2, Elevator x5): add their other floors, or delete any that aren't stairs

### Carlisle Hall (CAH)

- [ ] Floor 1: no outside doors are drawn, so 3 stairwells on the outside wall stand in as entrances: move them to the real doors
- [ ] Floor 1: 5 of 6 rooms have no door: add doors to 101, 101A, 102, 102A, 103
- [ ] Floor 3: 9 of 24 rooms have no door: add doors to 303, 306, 309, 310, 314, 315, 316, 317...
- [ ] 3 stairs/elevators are on one floor only (Stairs 3, Stairs 2, Stairs x5): add their other floors, or delete any that aren't stairs

### Civil Engineering Laboratory Building (CELB)

- Nothing flagged. Spot-check it against the diagrams.

### College Hall (CH)

- **Note:** Only floors B and 1 have diagrams.
- [ ] Floor B: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 1: 10 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] 2 stairs/elevators are on one floor only (Elevator 1, Elevator 1b): add their other floors, or delete any that aren't stairs

### College Park Center

- [ ] Floor 0: 26 of 119 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 1: 26 of 73 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 1: hallways are in 5 pieces (1193, 70, 67, 65, 4 m): connect them, unless the floor really is split
- [ ] Floor 2: 2 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2: 7 of 16 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 2: 8 of 9 rooms have no door: add doors to 2101, 2102, 2105, 2110, 2114, 2118, 2119, 2120
- [ ] Floor 2: hallways are in 10 pieces (509, 69, 26, 4, 3, 2, 2, 1, 1, 1 m): connect them, unless the floor really is split
- [ ] 50 stairs/elevators are on one floor only (Stairs 8, Stairs x2, Stairs 4, Stairs x8, Stairs x9, Stairs x10, Stairs x11, Stairs x12, Stairs x13, Stairs x14, Stairs x15, Stairs x16, Stairs x17, Stairs x18, Stairs x19, Stairs x20, Stairs x21, Stairs x22, Stairs x23, Stairs x24, Stairs x25, Stairs x26, Stairs x27, Stairs x28, Stairs x29, Stairs x32, Stairs x33, Stairs x34, Stairs x35, Stairs x38, Stairs x40, Stairs x41, Stairs x42, Stairs x43, Stairs x44, Stairs x45, Stairs x46, Stairs x47, Stairs x48, Stairs x49, Stairs x50, Stairs x51, Stairs x52, Stairs 3, Stairs x56, Elevator x1, Elevator x2, Elevator x3, Elevator x4, Elevator x5): add their other floors, or delete any that aren't stairs

### Dan Dipert Welcome Center

- **Note:** The 2 diagrams cover only the south end of the map's outline, so the fit stretched the floor (+28%). Place it by hand on the south end.
- [ ] Floor 1: size may be off by +28%: check it against the map outline
- [ ] Floor 1: 7 of 19 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 1: 4 of 12 rooms have no door: add doors to 104A, 104B, 106, 112

### Environmental Health and Safety (EHS)

- Nothing flagged. Spot-check it against the diagrams.

### Fine Arts Building (FA)

- [ ] Floor 1: hallways are in 5 pieces (808, 184, 14, 7, 7 m): connect them, unless the floor really is split
- [ ] Floor 1: room numbers probably misread: 1018, 1138
- [ ] Floor 2: 36 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2 piece 1: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 2: hallways are in 4 pieces (868, 12, 11, 2 m): connect them, unless the floor really is split
- [ ] Floor 2: room numbers probably misread: 2100, 2101, 2102, 2102A, 2105, 2105A, 2106A, 2106C, 2109B, 2111, 2112, 2113, 2114, 2117, 2118, 2119, 2120, 2121, 2121A, 2122, 2123
- [ ] Floor 3: hallways are in 2 pieces (574, 11 m): connect them, unless the floor really is split
- [ ] Floor 3: room numbers probably misread: 3451
- [ ] Floor 4: hallways are in 2 pieces (121, 2 m): connect them, unless the floor really is split
- [ ] 15 stairs/elevators are on one floor only (Stairs x2, Stairs x3, Stairs x5, Stairs x6, Stairs x7, Stairs x9, Stairs x10, Stairs x11, Stairs x12, Stairs x13, Stairs x20, Stairs x21, Stairs x22, Elevator x1, Elevator x5): add their other floors, or delete any that aren't stairs
- [ ] 2 stairs/elevators skip a floor (Stairs x24 [2 4], Stairs x27 [1 2 4]): add the missing stops

### General Academic Classroom Building (GACB)

- **Note:** The map's outline for GACB is too big (it wraps a courtyard). The building is about the 32 x 33 m southwest block. Anthony: reshape the outline in the Campus Digitizer, then recheck placement.
- [ ] Floor 1: hallways are in 3 pieces (129, 9, 3 m): connect them, unless the floor really is split

### Hammond Hall (HH)

- **Note:** No floor 3 diagrams exist, so floor 3 is missing.
- [ ] Floor 1: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 1: hallways are in 2 pieces (30, 10 m): connect them, unless the floor really is split
- [ ] Floor 1: room numbers probably misread: 1321
- [ ] Floor 5: hallways are in 2 pieces (42, 12 m): connect them, unless the floor really is split

### Life Science Building (LS)

- [ ] Floor 6 can't be reached: no stairs or elevator connects it to the rest. Add the missing stairs.
- [ ] Floor B: hallways are in 2 pieces (282, 4 m): connect them, unless the floor really is split
- [ ] Floor 1: 16 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 1: hallways are in 2 pieces (328, 57 m): connect them, unless the floor really is split
- [ ] Floor 2: hallways are in 2 pieces (114, 96 m): connect them, unless the floor really is split
- [ ] Floor 3: hallways are in 2 pieces (233, 12 m): connect them, unless the floor really is split
- [ ] Floor 4: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 4: hallways are in 2 pieces (123, 81 m): connect them, unless the floor really is split
- [ ] Floor 6: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 6: 5 of 12 rooms have no door: add doors to 602A, 603A, 603B, 603C, 610
- [ ] 10 stairs/elevators are on one floor only (Stairs x2, Stairs x3, Stairs x4, Stairs x6, Stairs x7, Stairs x9, Stairs x10, Elevator x2, Elevator x3, Elevator x4): add their other floors, or delete any that aren't stairs
- [ ] 5 stairs/elevators skip a floor (Stairs x1 [B 1 3], Stairs x5 [1 3], Stairs x8 [1 3], Elevator x5 [B 2 3 5], Elevator x6 [B 1 2 3 5]): add the missing stops

### Maverick Activities Center (MAC)

- **Note:** Most one-floor "stairs" on floor 1 are locker rows in the locker rooms: delete them.
- [ ] Floor 1: hallways are in 4 pieces (1774, 11, 5, 4 m): connect them, unless the floor really is split
- [ ] Floor 1: room numbers probably misread: 444
- [ ] Floor 2: 8 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2: 12 of 26 rooms have no door: add doors to 210, 220, 221, 222, 223, 224, 226, 227...
- [ ] Floor 2: hallways are in 2 pieces (596, 11 m): connect them, unless the floor really is split
- [ ] 19 stairs/elevators are on one floor only (Stairs 4, Stairs x3, Stairs x4, Stairs 5, Stairs x7, Stairs x8, Stairs x9, Stairs x10, Stairs 6, Stairs x13, Stairs x14, Stairs x15, Stairs x16, Stairs x17, Stairs x18, Stairs x19, Stairs x20, Elevator x1, Elevator x2): add their other floors, or delete any that aren't stairs

### Physical Education Building (PE)

- [ ] Floor 2: 1 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 2: hallways are in 3 pieces (21, 7, 6 m): connect them, unless the floor really is split
- [ ] Floor 2: room numbers probably misread: 114, 714A
- [ ] Floor 3: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] 8 stairs/elevators are on one floor only (Stairs x1, Stairs x2, Stairs x3, Stairs x4, Stairs x5, Stairs x6, Stairs x7, Stairs x9): add their other floors, or delete any that aren't stairs

### Pickard Hall (PKH)

- **Note:** Elevators below floor 6 were missed (plain squares in the core): add them.
- [ ] Floor 1: hallways are in 2 pieces (228, 2 m): connect them, unless the floor really is split
- [ ] Floor 2: 10 of 29 rooms have no door: add doors to 201, 206, 209, 210, 216, 217, 222A, 224...
- [ ] Floor 4: 21 of 82 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 5: 13 of 60 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 6: 20 of 84 rooms weren't traced (merged into the hallway): draw them
- [ ] 8 stairs/elevators are on one floor only (Stairs 2, Stairs 1, Stairs x5, Stairs 4, Stairs x7, Elevator 3, Elevator 2, Elevator x4): add their other floors, or delete any that aren't stairs
- [ ] 2 stairs/elevators skip a floor (Stairs x1 [1 3], Elevator 1 [1 6]): add the missing stops

### SEIR Building (SEIR)

- **Note:** No floor 2 diagrams exist, so floor 2 is missing.
- [ ] Floor B: room numbers probably misread: 1384
- [ ] Floor 1: 2 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 1: 36 of 75 rooms have no door: add doors to 110, 126, 127, 128, 129, 131A, 131B, 135...
- [ ] Floor 1: hallways are in 4 pieces (387, 69, 37, 2 m): connect them, unless the floor really is split
- [ ] Floor 1: room numbers probably misread: 1044, 1901, 557
- [ ] Floor 4: room numbers probably misread: 4044
- [ ] 7 stairs/elevators are on one floor only (Stairs 2b, Stairs x6, Stairs x9, Stairs 3, Stairs x11, Stairs x12, Elevator 3b): add their other floors, or delete any that aren't stairs
- [ ] 4 stairs/elevators skip a floor (Stairs 2 [1 4], Stairs x8 [B 1 4], Elevator 2 [B 4], Elevator 3 [B 1 4]): add the missing stops

### SWSH - UTA School of Social Work & CONHI Smart Hospital (SWSH)

- **Note:** Floor 4 is open-plan cubicles, traced as a web of hallways. Leave it or simplify it.
- [ ] Floor B can't be reached: no stairs or elevator connects it to the rest. Add the missing stairs.
- [ ] Floor B: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor B: 9 of 9 rooms have no door: add doors to B101, B102, B103, B104, B105, B106, B107, B108...
- [ ] Floor 1: 19 of 48 rooms have no door: add doors to 101, 102, 105, 109, 114, 116, 117, 118...
- [ ] Floor 1: hallways are in 3 pieces (479, 225, 2 m): connect them, unless the floor really is split
- [ ] Floor 2: 2 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2: 23 of 56 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 2: 9 of 33 rooms have no door: add doors to 207, 209, 210, 212, 216, 217, 219, 228...
- [ ] Floor 2: hallways are in 2 pieces (429, 3 m): connect them, unless the floor really is split
- [ ] Floor 2: room numbers probably misread: 145
- [ ] Floor 3: 16 of 75 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 3: room numbers probably misread: 1316, 13330, 1333N, 221, 3011
- [ ] Floor 4: 92 of 123 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 4: 8 of 31 rooms have no door: add doors to 401, 407, 411, 412, 417, 421, 424, 425
- [ ] Floor 4: hallways are in 2 pieces (549, 46 m): connect them, unless the floor really is split
- [ ] 12 stairs/elevators are on one floor only (Stairs 2, Stairs x3, Stairs x4, Stairs x6, Stairs 1, Stairs 1b, Stairs x11, Stairs x12, Stairs x16, Stairs x18, Stairs x19, Elevator x2): add their other floors, or delete any that aren't stairs
- [ ] 4 stairs/elevators skip a floor (Stairs x5 [1 3], Stairs 3 [1 2 4], Stairs x14 [1 2 4], Stairs 4 [2 4]): add the missing stops

### Science Hall (SH)

- [ ] Floor 1: hallways are in 3 pieces (337, 38, 10 m): connect them, unless the floor really is split
- [ ] Floor 1: room numbers probably misread: 1201
- [ ] Floor 2: hallways are in 3 pieces (170, 3, 3 m): connect them, unless the floor really is split
- [ ] 14 stairs/elevators are on one floor only (Stairs x1, Stairs x2, Stairs 2, Stairs x4, Stairs 1, Stairs x6, Stairs x8, Stairs x14, Stairs 1b, Stairs x17, Stairs x18, Elevator 1, Elevator x2, Elevator x5): add their other floors, or delete any that aren't stairs
- [ ] 3 stairs/elevators skip a floor (Stairs 2b [B 2 3], Stairs 2bb [1 4], Elevator 2 [1 3]): add the missing stops

### Studio Arts Center (SAC)

- **Note:** Four blocks around an open courtyard: the courtyard came out as a web of hallway (it is outdoors), and the map's outline leaves it out, so the fit looks low. The rooms line up with the blocks.
- [ ] Floor 1: 13 of 55 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 1: hallways are in 4 pieces (627, 22, 21, 3 m): connect them, unless the floor really is split
- [ ] Floor 1: room numbers probably misread: 1416A

### Swift Center

- [ ] Floor 2 can't be reached: no stairs or elevator connects it to the rest. Add the missing stairs.
- [ ] Floor 1: hallways are in 4 pieces (154, 56, 18, 2 m): connect them, unless the floor really is split
- [ ] Floor 1: room numbers probably misread: 1290, 1291
- [ ] Floor 2: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] 2 stairs/elevators are on one floor only (Stairs x1, Stairs x2): add their other floors, or delete any that aren't stairs

### Texas Hall (TXH)

- **Note:** Only the basement has diagrams.
- [ ] Floor B: hallways are in 3 pieces (171, 126, 19 m): connect them, unless the floor really is split
- [ ] Floor B: room numbers probably misread: K111A

### The Heights on Pecan

- [ ] Floor 1: no outside doors are drawn, so 2 stairwells on the outside wall stand in as entrances: move them to the real doors
- [ ] Floor 1: 12 of 53 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 2: 19 of 50 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 3: 14 of 48 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 4: 12 of 48 rooms weren't traced (merged into the hallway): draw them
- [ ] 1 stairs/elevators are on one floor only (Elevator x1): add their other floors, or delete any that aren't stairs

### Trimble Hall (TH)

- **Note:** Placement is right (the diagrams are drawn upside down). Nothing routes: the south breezeway entrance is ~38 m from any walkway. Anthony: trace a walkway to it in the Campus Digitizer.
- [ ] Floor 3 can't be reached: no stairs or elevator connects it to the rest. Add the missing stairs.
- Only 0 of 90 room doors can be reached from outside: check the entrances and that the hallways connect.
- [ ] Floor 1: 2 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 3: may be misplaced (lined up with the map outline only, not the other floors): check it lines up

### Trinity Hall

- **Note:** Traced from the 2021 Trinity Hall diagrams (archive folder TRIN). The older "Trinity" folder is Trinity House, a dorm that is not on the map.
- [ ] Floor 3 can't be reached: no stairs or elevator connects it to the rest. Add the missing stairs.
- [ ] Floor 1: 6 of 29 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 2: 6 of 29 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 3: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 3: 7 of 28 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 3: hallways are in 2 pieces (731, 29 m): connect them, unless the floor really is split
- [ ] Floor 3: room numbers probably misread: 02307, 1305
- [ ] 12 stairs/elevators are on one floor only (Stairs 1, Stairs x3, Stairs x4, Stairs x5, Stairs x6, Stairs x7, Stairs x8, Stairs x11, Elevator x1, Elevator 2, Elevator 1, Elevator x4): add their other floors, or delete any that aren't stairs

### UTA Police Department

- **Note:** The map joins the police department's two buildings into one outline, which may be why the fit is only 0.69: check the placement.
- [ ] Floor 1: size may be off by +28%: check it against the map outline

### University Administration Building (UAB)

- [ ] Floor B: 13 of 38 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 1: 1 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 1: 9 of 39 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 3: 16 of 56 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 4: 10 of 39 rooms weren't traced (merged into the hallway): draw them
- [ ] 4 stairs/elevators are on one floor only (Stairs x1, Stairs x3, Stairs x7, Elevator x1): add their other floors, or delete any that aren't stairs

### University Center (UC)

- [ ] Floor B: hallways are in 2 pieces (516, 4 m): connect them, unless the floor really is split
- [ ] Floor B: room numbers probably misread: 054, 120G, 1501
- [ ] Floor 1: 38 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 1: 42 of 132 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 1: hallways are in 2 pieces (3402, 26 m): connect them, unless the floor really is split
- [ ] Floor 1: room numbers probably misread: 2165
- [ ] 20 stairs/elevators are on one floor only (Stairs x1, Stairs x2, Stairs x3, Stairs x4, Stairs x5, Stairs x6, Stairs x7, Stairs x9, Stairs x10, Stairs x11, Stairs x12, Stairs x14, Stairs x16, Stairs x17, Stairs x18, Elevator x1, Elevator x2, Elevator x4, Elevator x6, Elevator x7): add their other floors, or delete any that aren't stairs

### Vandergriff Hall

- [ ] Floor 4 can't be reached: no stairs or elevator connects it to the rest. Add the missing stairs.
- [ ] Floor 1: 3 of 13 rooms weren't traced (merged into the hallway): draw them
- [ ] Floor 1: 4 of 10 rooms have no door: add doors to 120, E102, E120, M103
- [ ] Floor 1: hallways are in 2 pieces (228, 52 m): connect them, unless the floor really is split
- [ ] Floor 2: 2 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 3: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 4: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] 6 stairs/elevators are on one floor only (Stairs x2, Stairs x4, Stairs x5, Stairs x6, Stairs x7, Elevator x2): add their other floors, or delete any that aren't stairs

### West Hall

- [ ] Floor 1: may be misplaced (lined up with the map outline only, not the other floors): check it lines up
- [ ] Floor 1: hallways are in 13 pieces (1634, 5, 4, 4, 4, 4, 4, 4, 3, 3, 3, 2, 2 m): connect them, unless the floor really is split
- [ ] Floor 2: 5 doors to the outside one floor up: keep real entrances, delete balcony or patio doors
- [ ] Floor 2: hallways are in 2 pieces (123, 120 m): connect them, unless the floor really is split
- [ ] Floor 3: hallways are in 2 pieces (130, 113 m): connect them, unless the floor really is split
- [ ] Floor 4: hallways are in 2 pieces (132, 113 m): connect them, unless the floor really is split
- [ ] 2 stairs/elevators are on one floor only (Elevator x1, Elevator x2): add their other floors, or delete any that aren't stairs

## Not usable: trace by hand

### Kalpana Chawla Hall (KC)

- **Note:** Floors 2 and 3 are placed badly and most rooms merged into the hallway. Probably faster to trace by hand.

### The Lofts

- **Note:** Only 18 rooms found and the size is off by ~28%. Trace by hand.

### Thermal Energy Plant

- **Note:** Only 8 rooms found, fit 0.25. A plant building: probably not worth mapping.
