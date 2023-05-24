﻿---
title: Matrix class
second_title: Aspose.CAD for Python via .NET API References
description: 
type: docs
weight: 350
url: /aspose.cad/matrix/
is_root: false
---

## Matrix class

Replaces the GDI+ Matrix.



The Matrix type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/cad/python-net/aspose.cad/matrix/__init__/#) | Initializes a new instance of the Matrix class as the identity matrix. |
| [__init__](/cad/python-net/aspose.cad/matrix/__init__/#float-float-float-float-float-float) | Initializes a new instance of the [`Matrix`](/cad/python-net/aspose.cad/matrix) class. |
| [__init__](/cad/python-net/aspose.cad/matrix/__init__/#aspose.cad.RectangleF-list) | Initializes a new instance of the [`Matrix`](/cad/python-net/aspose.cad/matrix) class to the geometric transform defined by the specified rectangle and array of points. |
| [__init__](/cad/python-net/aspose.cad/matrix/__init__/#aspose.cad.Rectangle-list) | Initializes a new instance of the [`Matrix`](/cad/python-net/aspose.cad/matrix) class to the geometric transform defined by the specified rectangle and array of points. |


### Properties
| Property | Description |
| :- | :- |
| [elements](/cad/python-net/aspose.cad/matrix/elements) | Gets an array of floating-point values that represents the elements of this [`Matrix`](/cad/python-net/aspose.cad/matrix). |
| [m11](/cad/python-net/aspose.cad/matrix/m11) | Gets the matrix element at first row first column. Represents scale along X axis. |
| [m12](/cad/python-net/aspose.cad/matrix/m12) | Gets the matrix element at first row second column. Represents shear along Y axis. |
| [m21](/cad/python-net/aspose.cad/matrix/m21) | Gets the matrix element at second row first column. Represents shear along X axis. |
| [m22](/cad/python-net/aspose.cad/matrix/m22) | Gets the matrix element at second row second column. Represents scale along Y axis. |
| [m31](/cad/python-net/aspose.cad/matrix/m31) | Gets the matrix element at third row first column. Represents translation along X axis. |
| [m32](/cad/python-net/aspose.cad/matrix/m32) | Gets the matrix element at third row first column. Represents translation along Y axis. |
| [TYPE_IDENTITY](/cad/python-net/aspose.cad/matrix/type_identity) | An identity transform is one in which the output coordinates are
| [TYPE_TRANSLATION](/cad/python-net/aspose.cad/matrix/type_translation) | A translation moves the coordinates by a constant amount in x
| [TYPE_UNIFORM_SCALE](/cad/python-net/aspose.cad/matrix/type_uniform_scale) | A uniform scale multiplies the length of vectors by the same amount
| [TYPE_GENERAL_SCALE](/cad/python-net/aspose.cad/matrix/type_general_scale) | A general scale multiplies the length of vectors by different
| [TYPE_MASK_SCALE](/cad/python-net/aspose.cad/matrix/type_mask_scale) | This constant is a bit mask for any of the scale flag bits. |
| [TYPE_FLIP](/cad/python-net/aspose.cad/matrix/type_flip) | This flag bit indicates that the transform defined by this object
| [TYPE_QUADRANT_ROTATION](/cad/python-net/aspose.cad/matrix/type_quadrant_rotation) | This flag bit indicates that the transform defined by this object
| [TYPE_GENERAL_ROTATION](/cad/python-net/aspose.cad/matrix/type_general_rotation) | This flag bit indicates that the transform defined by this object
| [TYPE_MASK_ROTATION](/cad/python-net/aspose.cad/matrix/type_mask_rotation) | This constant is a bit mask for any of the rotation flag bits. |
| [TYPE_GENERAL_TRANSFORM](/cad/python-net/aspose.cad/matrix/type_general_transform) | This constant indicates that the transform defined by this object


### Methods
| Method | Description |
| :- | :- |
| [scale](/cad/python-net/aspose.cad/matrix/scale/#float-float-aspose.cad.MatrixOrder) | Applies the specified scale vector (scaleX and scaleY) to this [`Matrix`](/cad/python-net/aspose.cad/matrix) using the specified order. |
| [scale](/cad/python-net/aspose.cad/matrix/scale/#float-float) | Applies the specified scale vector (scaleX and scaleY) to this Matrix using (default) Prepend order. |
| [translate](/cad/python-net/aspose.cad/matrix/translate/#float-float-aspose.cad.MatrixOrder) | Applies the specified translation vector to this Matrix in the specified order. |
| [translate](/cad/python-net/aspose.cad/matrix/translate/#float-float) | Applies the specified translation vector to this [`Matrix`](/cad/python-net/aspose.cad/matrix) using (default) Prepend order. |
| [multiply](/cad/python-net/aspose.cad/matrix/multiply/#aspose.cad.Matrix-aspose.cad.MatrixOrder) | Multiplies this Matrix by the matrix specified in the matrix parameter, and in the order specified in the order parameter. |
| [multiply](/cad/python-net/aspose.cad/matrix/multiply/#aspose.cad.Matrix) | Multiplies this Matrix by the matrix specified in the matrix parameter using (default) Prepend order. |
| [rotate](/cad/python-net/aspose.cad/matrix/rotate/#float-aspose.cad.MatrixOrder) | Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the specified order. |
| [rotate](/cad/python-net/aspose.cad/matrix/rotate/#float) | Applies a clockwise rotation of an amount specified in the angle parameter, around the origin (zero x and y coordinates) for this Matrix in the default (Prepend) order. |
| [rotate_at](/cad/python-net/aspose.cad/matrix/rotate_at/#float-aspose.cad.PointF-aspose.cad.MatrixOrder) | Applies a clockwise rotation about the specified point to this Matrix in the specified order. |
| [rotate_at](/cad/python-net/aspose.cad/matrix/rotate_at/#float-aspose.cad.PointF) | Applies a clockwise rotation about the specified point to this Matrix in the default (Prepend) order. |
| [get_elements](/cad/python-net/aspose.cad/matrix/get_elements/#) | Gets the copy of matrix elements. |
| [transform_points](/cad/python-net/aspose.cad/matrix/transform_points/#list) | Applies the geometric transform represented by this [`Matrix`](/cad/python-net/aspose.cad/matrix) to a specified array of points. |
| [reset](/cad/python-net/aspose.cad/matrix/reset/#) | Resets this Matrix to have the elements of the identity matrix. |
| [equals](/cad/python-net/aspose.cad/matrix/equals/#aspose.cad.Matrix-aspose.cad.Matrix) | Determines whether two matrixes are equal. |



### Remarks 


Most algorithms taken from Sun's AffineTransform.java.
Java's names for matrix elements used internally.
Map of java names to .net ones to description:
m00     M11     Scale X
m10     M12     Shear Y
m01     M21     Shear X
m11     M22     Scale Y
m02     M31     Translate X
m12     M32     Translate Y

### See Also
* module [`aspose.cad`](..)
* class [`Matrix`](/cad/python-net/aspose.cad/matrix)