# numpyascii Package

Asciiart for defining and visualizing 1D, 2D, 3D numpy matrices

Example
```
import numpy as np
from numpyascii_GonenRaveh import numpyascii as npa
npa.selftest()

x = npa.np3(
'''             
   +---+---+----+
  /   /   /   2/| 
 /   /   /    / .
+---+---+---+/ /|
| 0 |...| 8 | / .
+---+---+---+/ /|
|...|   |   | / .
+---+---+---+/ /
|10 |   |   | /
+---+---+---+/
''')
print('computed shape=',x.shape, 'SUCCESS=', x.shape==(1+10-0,1+8-0,1+2-0))
```
