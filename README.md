# Expression2 [![License](https://img.shields.io/github/license/Vurv78/expression2-public-e2s?color=red)](https://opensource.org/licenses/MIT) [![github/Vurv78](https://img.shields.io/discord/824727565948157963?label=Discord&logo=discord&logoColor=ffffff&labelColor=7289DA&color=2c2f33)](https://discord.gg/epJFC6cNsw)

> A collection of my public E2 libraries and chips. Note this is mostly bad code and should not be taken as learning material.

*❔ Want to code Expression2? Use my [Expression-LS](https://github.com/Vurv78/Expression-LS) for VSCode!*  
*Also, I've been working on a successor to E2, [Expressive](https://github.com/Vurv78/Expressive)*

## Note
Libraries are very inefficient. There's a 20 ops penalty just to use a user defined function. Use these sparingly.

## Installing
__Method 1 - Copy into gmod:__
  1. Go on the chip page.
  2. Click the "raw" button.
  3. CTRL+S (Save the file)
  3. Drag it into your [STEAMFOLDER]/steamapps/common/GarrysMod/garrysmod/data/expression2 folder

__Method 2: Paste into E2 Editor.__
1. Just copy and paste the code into your editor.

__Both Methods:__
Read for any additional instructions in the form of e2 comments.

## E2 Library Usage:
  #### Libraries:
  1. Use ``#include "e2name"`` in your code with e2name being the name of the e2 you saved the library in.
  2. Be aware that all of the functions will appear red as if the e2 doesn't recognize them but it'll work. This is because of the e2's editor not going over ``#include``s
