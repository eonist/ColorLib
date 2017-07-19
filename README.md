# **ColorLib**

<img width="100" alt="img" src="https://rawgit.com/stylekit/img/master/ColorLib.svg">

- Easily convert between color types: ColorLib, RGB, CMYK, HSL, HSB, HSB, NSColor, CGColor, CLColor
- Supporting 7 "Hex" color types:


There are 7 "hex" color formats: ""#FF0000","0xFF0000", "FF0000", "F00", "red", 0x00FF00 , 16711935
```
ColorParser.nsColor("#FF0000",1)//red nsColor
ColorParser.nsColor("FF0",1)//red nsColor
ColorParser.nsColor("0xFF0000",1)//red nsColor
ColorParser.nsColor("#FF0000",1)//red nsColor
ColorParser.nsColor("FF0000",1)//red nsColor
ColorParser.nsColor(0xFF0000,1)//red nsColor
ColorParser.nsColor(16711935,1)//red nsColor
```
