# EyeLinkCoreGraphicsPsychoPy

The `EyeLinkCoreGraphicsPsychoPy.py` file in this repository is copyrighted by SR Research Ltd (C) 2018-2021.
See the `LICENSE` file in this repository.

This repository is intended to make `EyeLinkCoreGraphicsPsychoPy.py` easily accessible via a `pip` install.

## Versions, licenses, and redistribution

The version distributed here corresponds to version `2021.3.31` (released 2021-03-31).
It is licensed under GPLv2, copyright SR Research Ltd (see `LICENSE`).

There are newer versions available (for example `2023.1.1`, released 2023-08-23).
However, the never versions are **no longer licensed under the GPLv2 license**.
Redistribution of the never versions is not permitted,
and thus the repository here will not be updated with never versions.

If you want to use the most recent version of `EyeLinkCoreGraphicsPsychoPy.py`,
please go directly via the SR Research support.

That said, the changed lines from version `2021.3.31` to `2023.1.1` are minimal,
and you will most likely be able to use the presently redistributed version without problems.

## Installation

You can clone this repository and run `pip install -e .` from the root of the clone.

Alternatively, you can install it directly from GitHub (recommended):

`pip install -U https://github.com/sappelhoff/EyeLinkCoreGraphicsPsychoPy/archive/refs/heads/main.tar.gz`

## Usage

Typically, SR Research recommends that you include the `EyeLinkCoreGraphicsPsychoPy.py` file in your experiment folder.
Alternatively you can just install this repository (see above) and call

```python
from EyeLinkCoreGraphicsPsychoPy import EyeLinkCoreGraphicsPsychoPy
```

as usual.
The rest of your script and the SR Research examples can remain unaffected.

Note that SR Research also includes some sound files next to their `EyeLinkCoreGraphicsPsychoPy.py`.
These are not shipped as part of this repository, so sound will be disabled.
