# ASM2d-GHG/N₂O

Python package for ASM2d-GHG/N₂O dynamic process modelling.

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
from asm2dghg import asm2d_ghg, clarifiers, combiner, delay
from asm2dg import asm2d_g, clarifiers, combiner, delay
```

## Current modules

The package currently provides:

- `asm2d_n2o` : ASM2d-GHG/N₂O biochemical reactor
- `asm2d_ghg` : alias of `asm2d_n2o`
- `asm2d_g` : alias of `asm2d_n2o`
- `clarifiers` : primary and secondary clarifier
- `combiner` : two-stream mixer
- `delay` : hydraulic delay


## License and attribution

See:

- `LICENSE`
- `THIRD_PARTY_NOTICES.md`
