PNGLib Documentation
## Docs Created with e2tinytokenizer
More @https://github.com/Vurv78/expression2-public-e2s

## Functions that return **number**

### number = table:done()
 Returns whether all of the pixels of the png have been filled.

## Functions that return **table**

### table = table:output()
 Returns the output table of the png. Concatenate this with an empty string to get the actual string output.
### table = createPNG(Width,Height)
 Create a default RGB Image. Acts like createPNG(Width,Height,"rgb")

## Functions that return **void**

### void = table:writeVector4Fast(V:vector4)
 Write RGBA Pixel with a vector4 fast (Doesn't round for you, can lead to image corruption if given decimals!) (Make sure your png is rgba mode or it won't work)
### void = table:write(Pixels:table)
 Manual mode to write to a png image, I wouldn't use this if I were you.
### void = table:adler32(Data:table , Index, Len)
 Internal function used by the image library. Do not use this!
### void = table:writeBytes(Data:table)
 Internal function used by the image library. Do not use this!
### void = table:crc32(Data:table, Index, Len)
 Internal function used by the image library. Do not use this!
### void = table:writeRGB(R,G,B)
 Write RGB Pixel (Make sure your png is rgb mode or it won't work)
### void = table:export(FilePath:string)
 Exports the png data to a filepath given (FilePath)
### void = table:writeVectorFast(V:vector)
 Write RGB Vector Fast (Doesn't round for you, can lead to image corruption if given decimals!) (Make sure your png is rgb mode or it won't work)
### void = table:writeVector4(V:vector4)
 Write RGBA Pixel with a vector4 (Make sure your png is rgba mode or it won't work)
### void = table:writeRGBAFast(R,G,B,A)
 Write RGBA Pixel Fast (Doesn't round for you, can lead to image corruption if given decimals!) (Make sure your png is rgba mode or it won't work)
### void = table:writeVector(V:vector)
 Write RGB Vector (Make sure your png is rgba mode or it won't work)
### void = table:writeRGBA(R,G,B,A)
 Write RGBA Pixel (Make sure your png is rgba mode or it won't work)
### void = table:writeRGBFast(R,G,B)
 Write RGB Pixel Fast (Make sure your png is rgb mode or it won't work)
### void = putBigUint32(Val,Tbl:table,Index)
 Internal function used by the image library. Do not use this!
