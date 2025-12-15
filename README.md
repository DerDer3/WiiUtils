# WiiUtils
Set of command line tools to convert PMP and KCL files into a JSON format. Specifically for usage in my PMP Editor

# Usage
```text
./WiiUtils [options] <input_file>


Options:
  -kd     Decode a kcl file
  -pd     Decode a pmp file
  -pe     Encode a pmp file
```


## KCL Decode
Decodes a kcl file into a JSON array of triangles containing normal data and collision flag

## PMP Decode
Decodes a pmp file into a JSON containing arrays for object data, route data, and point data

## PMP Encode
Encodes a file back into a pmp file. Input file is a dump of the data line by line, primarily useful for PMP Editor.
