# pb_ColorUtil

A set of types and utilities for converting between color formats in C#.

### Get Color Name

`pb_ColorUtil.GetColorName(Color color)`

Returns the name of the closest matching color (over 1000 unique names).

![](colorwheel.gif?raw=true)

http://en.wikipedia.org/wiki/List_of_colors:_A%E2%80%93F

### New Color Types

- HSV - `pb_HsvColor`
- XYZ - `pb_XYZColor`
- CIE-Lab - `pb_CIE_Lab_Color`

### Conversion Methods

- RGB to XYZ
- XYZ to CIE-Lab
- HSV to RGB
- RGB to HSV
