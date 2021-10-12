# EyeLinkCoreGraphicsPsychoPy

The `EyeLinkCoreGraphicsPsychoPy.py` file in this repository is copyrighted by SR Research Ltd (C) 2018-2021.
See the `LICENSE` file in this repository.

This repository is intended to make `EyeLinkCoreGraphicsPsychoPy.py` easily accessible via a `pip` install.

## Installation

You can clone this repository and run `pip install -e .` from the root of the clone.

Alternatively, you can install it directly from GitHub (recommended):
`pip install https://github.com/sappelhoff/EyeLinkCoreGraphicsPsychoPy/archive/main.tar.gz`

## Usage

Typically, SR-Research recommends that you include the `EyeLinkCoreGraphicsPsychoPy.py` file in your experiment folder.
Alternatively you can just install this repository (see above) and call

```python
from EyeLinkCoreGraphicsPsychoPy import EyeLinkCoreGraphicsPsychoPy
```
as usual. The rest of your script and the SR-Research examples can remain unaffected.

Note that SR-Research also includes some sound files next to their `EyeLinkCoreGraphicsPsychoPy.py`.
These are not shipped as part of this repository, so sound will be disabled.
