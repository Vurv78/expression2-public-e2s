## Public Expression2 Code
[![Poggers](https://forthebadge.com/images/badges/powered-by-water.svg)](https://forthebadge.com)

A collection of my public E2 libraries and chips.
Make any issues for bugs you find, I might fix them. I don't care what you do with my e2 chips, just don't be a skid and claim it's your code.

Some of these E2s use my webserver, here's the source: https://github.com/Vurv78/Webserver.

Also, to note before looking into my libraries: (LIBRARIES NOT CHIPS)
Libraries in e2 are very inefficient. They have a flat 20 ops penalty for calling any user function once and they don't have syntax highlighting. I would not recommend getting used to using libraries such as the math or stringext ones I or anyone else have made as they really only provide small functionality you can do yourself without a userfunction. But if you don't care about OPS / efficiency, then go for it.

## Installing
__Method 1 - Copy into GMOD:__
  1. Go on the chip page.
  2. Click the "raw" button.
  3. CTRL+S (Save the file)
  3. Drag it into your [STEAMFOLDER]/steamapps/common/GarrysMod/garrysmod/data/expression2 folder

__Method 2: Just copy it into your E2 Editor.__

__Both Methods:__
Read for any additional instructions in the form of e2 comments.
## E2 Library Usage:
  #### Libraries:
  1. Use #include "e2name" in your code with e2name being the name of the e2 you saved the library in.
  2. Be aware that all of the functions will appear red as if the e2 doesn't recognize them but it'll work. This is because of the e2's editor not going over #include s
