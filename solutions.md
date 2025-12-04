# Workshop PoC Security - OSINT Solutions

### Step 1 - Find the city (Easy)

**Target Image:** https://i.ibb.co/2YJZTD0/easy.jpg

**What I did:**
Looked at the image carefully for any visible text, signs, or recognizable landmarks. I already saw this building it is Tour Oxygène, and checked on the map to check if i was right, it is in Lyon around Part Dieu

**Findings:**

- City: Lyon
- Key identifiers: Building style and own knowledge

---

### Step 2 - Find the GPS coordinates (Easy)

**Target:** Video file `Easy.mp4` in the repository

**What I did:**
Used google images and put the images of the bridge, fidn out that it was in Paris Le pont de la rue de l'Ourcq

**Findings:**

- GPS Coordinates: 48° 53′ 24″ N, 2° 22′ 58″ E
- Creation date: April 8, 2021 at 15:38:33

---

### Step 3 - Find the GPS coordinates (Medium)

**Target Image:** https://i.ibb.co/0FxmgTb/medium-chall.jpg

**What I did:**
Downloaded the image and ran exiftool but again no GPS data embedded. This one's tougher since it's marked as medium difficulty. Started by examining the architecture - what region does this look like? Checked the sun angle and shadows to estimate time of day and potentially hemisphere. Looking for any unique features like specific building styles, signs, or natural landmarks. Used Google Lens and reverse image search but being careful since sometimes these don't work on obscure locations. Might need to narrow down region first then zoom in on Google Earth.

**Findings:**

- GPS Coordinates: _(Still working on it)_
- Confidence level: _(Low so far)_
- Key identifiers: _Architecture style suggests X region, vegetation type, shadows pointing Y direction_
