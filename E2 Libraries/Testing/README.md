# PNGLib Documentation
## Docs Created with e2tinytokenizer
More @https://github.com/Vurv78/expression2-public-e2s

## Functions that return **number**

### ![Number](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png) = table:done()
 Returns whether all of the pixels of the png have been filled.

## Functions that return **table**

### ![Table](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Table.png) = createPNG(Width ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), Height ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), ColorMode ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png))
 Creates a png image object with colormode specified (rgb or rgba)
### ![Table](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Table.png) = createPNG(Width ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), Height ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Create a default RGB Image. Acts like createPNG(Width,Height,"rgb")
### ![Table](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Table.png) = table:output()
 Returns the output table of the png. Concatenate this with an empty string to get the actual string output.

## Functions that return **void**

### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = putBigUint32(Val ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), Tbl ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Table.png), Index ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Internal function used by the image library. Do not use this!
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeBytes(Data ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Table.png))
 Internal function used by the image library. Do not use this!
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:adler32(Data ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Table.png), Index ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), Len ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Internal function used by the image library. Do not use this!
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeBytes(Data ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Table.png),  Index ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png),  Len ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Internal function used by the image library. Do not use this!
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:export(FilePath ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-String.png))
 Exports the png data to a filepath given (FilePath)
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:write(Pixels ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Table.png))
 Manual mode to write to a png image, I wouldn't use this if I were you.
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeBytes(Data ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Table.png), Index ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Internal function used by the image library. Do not use this!
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeRGBA(R ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), G ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), B ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), A ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Write RGBA Pixel (Make sure your png is rgba mode or it won't work)
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeVector4(V ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Vector4.png))
 Write RGBA Pixel with a vector4 (Make sure your png is rgba mode or it won't work)
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeVectorFast(V ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Vector.png))
 Write RGB Vector Fast (Doesn't round for you, can lead to image corruption if given decimals!) (Make sure your png is rgb mode or it won't work)
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeRGBAFast(R ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), G ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), B ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), A ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Write RGBA Pixel Fast (Doesn't round for you, can lead to image corruption if given decimals!) (Make sure your png is rgba mode or it won't work)
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:crc32(Data ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Table.png),  Index ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png),  Len ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Internal function used by the image library. Do not use this!
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeVector(V ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Vector.png))
 Write RGB Vector (Make sure your png is rgba mode or it won't work)
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeRGBFast(R ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), G ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), B ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Write RGB Pixel Fast (Make sure your png is rgb mode or it won't work)
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeRGB(R ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), G ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png), B ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Number.png))
 Write RGB Pixel (Make sure your png is rgb mode or it won't work)
### ![Void](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Void.png) = table:writeVector4Fast(V ![](https://raw.githubusercontent.com/wiki/wiremod/wire/Type-Vector4.png))
 Write RGBA Pixel with a vector4 fast (Doesn't round for you, can lead to image corruption if given decimals!) (Make sure your png is rgba mode or it won't work)
