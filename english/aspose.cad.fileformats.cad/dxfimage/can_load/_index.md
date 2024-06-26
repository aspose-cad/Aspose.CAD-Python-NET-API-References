﻿---
title: can_load method
second_title: Aspose.CAD for Python via .NET API References
description: 
type: docs
weight: 40
url: /python-net/aspose.cad.fileformats.cad/dxfimage/can_load/
is_root: false
---

## can_load {#str}

Determines whether image can be loaded from the specified file path.


### Returns 


`true` if image can be loaded from the specified file; otherwise, `false`.


```python
def can_load(self, file_path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The file path. |

### Example 


Checks whether loading of a drawing is possible


## can_load {#io.RawIOBase}

Determines whether image can be loaded from the specified stream.


### Returns 


`true` if image can be loaded from the specified stream; otherwise, `false`.


```python
def can_load(self, stream):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The stream to load from. |

### Example 


Checks whether loading of a drawing is possible from the stream specified


## can_load {#str-aspose.cad.LoadOptions}

Determines whether an image can be loaded from the specified file path and optionally using the specified open options


### Returns 


`true` if an image can be loaded from the specified file; otherwise, `false`.


```python
def can_load(self, file_path, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| file_path | str | The file path. |
| load_options | [`LoadOptions`](/cad/python-net/aspose.cad/loadoptions) | The load options. |

### Example 


Checks whether loading of a drawing is possible with specified encoding


## can_load {#io.RawIOBase-aspose.cad.LoadOptions}

Determines whether image can be loaded from the specified stream and optionally using the specified `load_options`.


### Returns 


`true` if image can be loaded from the specified stream; otherwise, `false`.


```python
def can_load(self, stream, load_options):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| stream | io.RawIOBase | The stream to load from. |
| load_options | [`LoadOptions`](/cad/python-net/aspose.cad/loadoptions) | The load options. |

### Example 


Checks whether loading of a drawing is possible from the stream specified with a corresponding encoding



### See Also
* module [`aspose.cad.fileformats.cad`](../../)
* class [`DxfImage`](/cad/python-net/aspose.cad.fileformats.cad/dxfimage)
