﻿---
title: GradientStop class
second_title: Aspose.CAD for Python via .NET API References
description: 
type: docs
weight: 80
url: /python-net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/
is_root: false
---

## GradientStop class

The gradient stop.
The GradientStop element is used by both the LinearGradientBrush and RadialGradientBrush elements to define the location
and range of color progression for rendering a gradient.
For linear gradient brushes, the offset value of 0.0 is mapped to the start point of the gradient,
and the offset value of 1.0 is mapped to the end point.
Intermediate offset values are interpolated between these two points to determine their location.
For radial gradient brushes, the offset value of 0.0 is mapped to the gradient origin location.
The offset value of 1.0 is mapped to the circumference of the ellipse as determined by the center,
x radius, and y radius.Offsets between 0.0 and 1.0 are positioned at a location interpolated between these points.



The GradientStop type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/cad/python-net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/__init__/#) | Constructs a new instance of GradientStop |


### Properties
| Property | Description |
| :- | :- |
| [color](/cad/python-net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/color) | Gets or sets the color.
| [offset](/cad/python-net/aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto/gradientstop/offset) | Gets or sets the offset.



### See Also
* module [`aspose.cad.fileformats.dwf.dwfxps.fixedpage.dto`](..)