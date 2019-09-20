# postscript

## Running PostScript:
* GhostScript exe:
    * "\Program Files\gs\gs9.27\bin\gswin64c.exe"

## Arithmetic

```PS
x1 x2 sub dup mul
y1 y2 sub dup mul
add sqrt
```

This is the same as `sqrt((x1 - x2) * (x1 - x2) + (y1 - y2) * (y1 - y2))