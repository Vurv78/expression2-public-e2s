### PNGLib by Vurv in E2, made off of https://github.com/wyozi/lua-pngencoder/

## How to use:
```golo
# Example of how to use the library
P = createPNG(2,2)
P:writeVectorFast(vec(255,0,0))
P:writeVectorFast(vec(0,255,0))
P:writeVectorFast(vec(0,0,255))
P:writeRGBFast(255,255,255)
print(P:done())
P:export("test.txt") # Will put the image in data/e2files/test.txt rename it to test.png to see the png!

```


### Changelogs:

## Version 1.1
~ Renamed writePixel to writeVector
+ writeVectorFast(VectorRGB)
+ writeRGB(R,G,B)
+ writeRGBFast(R,G,B)
~ Updated writePixel/Vector to round numbers given as not to break the image
+ Png:export(FilePath)
+ Png:output()

NOTE:
Only use writeVectorFast/writeRGBFast if you know your digits are rounded so they won't break the image.

## Version 1.0
Created the library.
