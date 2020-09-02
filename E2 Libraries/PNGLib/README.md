### PNGLib by Vurv in E2, made off of https://github.com/wyozi/lua-pngencoder/

## How to use:
```golo
# Example of how to use the library
P = createPNG(2,2)
P:writeVectorFast(vec(255,0,0))
P:writeRGB(28.238,0,252.23)
P:writeVector(vec(248.92428,0,255))
P:writeRGBFast(255,255,255)
print(P:done())
P:export("test.txt") # Will put the image in data/e2files/test.txt rename it to test.png to see the png!

```


### Changelogs:

## Version 1.1
```golo
# Changed Renamed writePixel to writeVector
# Added writeVectorFast(VectorRGB)
# Added writeRGB(R,G,B)
# Added writeRGBFast(R,G,B)
# Changed Updated writePixel/Vector to round numbers given as not to break the image
# Added Png:export(FilePath)
# Added Png:output()
```

NOTE:
Only use writeVectorFast/writeRGBFast if you know your digits are rounded so they won't break the image.

## Version 1.0
Created the library.
