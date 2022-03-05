# Jupyter notebook examples of the pip version of Soft Potato

For more info, visit [Soft Potato](https://softpotato.xyz).

## Install
``` python
pip3 install softpotato

```

## Usage
``` python
from softpotato import *
import softpotato as sp

disc = sp.calc.MicroDisc(a=1e-4)
iLim = disc.iLim
print(iLim)

```
## Directory tree

See one of the following for examples on how to use the script version of Soft Potato.

* calc/
    * microdisc_LSV
    * microdisc_CA
    * Cottrell
    * Randles-Sevcik
* sim/
    * MacroE-BI
