# ASM2d-GHG/N₂O pH-Adjust

Python package for ASM2d-GHG/N₂O pH-Adjust dynamic process modelling.

## Installation

The same compiled model can be installed using one of three package names:

```bash
pip install asm2dn2o
```

or:

```bash
pip install asm2dghg
```

or:

```bash
pip install asm2dg
```

## Import

```python
from asm2dn2o import asm2d_n2o, asm2d_ghg, asm2d_g
from asm2dn2o import clarifiers, combiner, delay
```

Alternative alias imports:

```python
from asm2dghg import asm2d_n2o, clarifiers, combiner, delay, PCM_speciation_DAE, flotation, ASM2dmode_GHG_pH, ...
from asm2dg import asm2d_n2o, clarifiers, combiner, delay, PCM_speciation_DAE, flotation, ASM2dmode_GHG_pH, ...
```



## License and attribution

See:

- `LICENSE`
- `THIRD_PARTY_NOTICES.md`
