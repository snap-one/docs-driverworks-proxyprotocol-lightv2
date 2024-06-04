## What was New in 3.3.1

The capability: [color\_trace\_tolerance][1] has been modified to accept a Delta value of \> .01. When provided, the CIELa*b* tolerance formula is used to determining if a color is the as another color in the system.

The following Conversion Commands have been enhanced to include an optional parameter: gamut. This parameter allows for the specification of a gamut type for use in the conversions.

- [ColorHSVtoXY][2]
- [ColorXYtoHSV][3]
- [ColorRGBtoXY][4]
- [ColorXYtoRGB][5]



[1]:	https://expert-adventure-1w2nllv.pages.github.io/#light-v2-capabilities-color_trace_tolerance
[2]:	https://expert-adventure-1w2nllv.pages.github.io/#light-v2-conversion-commands-colorhsvtoxy
[3]:	https://expert-adventure-1w2nllv.pages.github.io/#light-v2-conversion-commands-colorxytohsv
[4]:	https://expert-adventure-1w2nllv.pages.github.io/#light-v2-conversion-commands-colorrgbtoxy
[5]:	https://expert-adventure-1w2nllv.pages.github.io/#light-v2-conversion-commands-colorxytorgb