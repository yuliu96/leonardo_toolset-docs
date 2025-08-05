# Leonardo: a toolset to remove sample-induced aberrations in light sheet microscopy images 

[![Build Status](https://github.com/peng-lab/leonardo_toolset/workflows/Build%20Main/badge.svg)](https://github.com/peng-lab/leonardo_toolset/actions)
---

*Leonardo* is a toolbox able to resolve all sample-induced aberrations in selective plane illumination microscopy (SPIM, also called light-sheet fluorescence microscopy, LSFM) by using two major modules: (1) **DeStripe** removes the stripe artifacts caused by light absorption; (2) **Fuse** reconstructs one single high-quality image from dual-sided illumination and/or dual-sided detection while eliminating optical distortions (ghosts) caused by light refraction. 

## Tutorials:

For a quick start, you can walk through [our tutorials and example notebooks](https://leonardo-toolset.readthedocs.io/en/latest/tutorials.html). You can easily run it on Google Colab by clicking on the badge.

## Installation:

**Stable Release:** `pip install leonardo_toolset`<br>
**Development Head:** `pip install git+https://github.com/peng-lab/leonardo_toolset.git`

> **Note**: Requires **Python 3.10 or newer**.

**Napari plugins can be installed separately:**
- Fusion plugin: `pip install lsfm_fusion_napari`  
- Destripe plugin: `pip install lsfm_destripe_napari`

## Development:

See [CONTRIBUTING.md](CONTRIBUTING.md) for information related to developing the code.

**MIT license**

