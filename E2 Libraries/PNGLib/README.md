### PNGLib by Vurv in E2, made off of https://github.com/wyozi/lua-pngencoder/

## How to use (Version 1.2):
```golo
P = createPNG(2,2,"rgb") # Third argument is optional
P:writeVectorFast(vec(255,0,0))
P:writeRGB(28.238,0,252.23)
P:writeVector(vec(248.92428,0,255))
P:writeRGBFast(255,255,255)
print(P:done())
P:export("test.txt") # Will put the image in data/e2files/test.txt rename it to test.png to see the png!
```


### Changelogs:

## Version 1.2 -- RGBA Images
```golo
# Added createPNG(ResX,ResY,ColorType) (ColorType can be "rgb" or "rgba"), it is optional however.
# Added writeVector4(Vector4RGB)
# Added writeVector4Fast(Vector4RGB)
# Added writeRGBA(R,G,B,A)
# Added writeRGBAFast(R,G,B,A)
# Changed Updated some functions to be more efficient in rounding by using lua methods (writeVector)
```

## Version 1.1 -- Bug Fixes + writeRGB
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
