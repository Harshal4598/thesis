<!-- These are examples of badges you might want to add to your README:
     please update the URLs accordingly

[![Built Status](https://api.cirrus-ci.com/github/<USER>/thesis.svg?branch=main)](https://cirrus-ci.com/github/<USER>/thesis)
[![ReadTheDocs](https://readthedocs.org/projects/thesis/badge/?version=latest)](https://thesis.readthedocs.io/en/stable/)
[![Coveralls](https://img.shields.io/coveralls/github/<USER>/thesis/main.svg)](https://coveralls.io/r/<USER>/thesis)
[![PyPI-Server](https://img.shields.io/pypi/v/thesis.svg)](https://pypi.org/project/thesis/)
[![Conda-Forge](https://img.shields.io/conda/vn/conda-forge/thesis.svg)](https://anaconda.org/conda-forge/thesis)
[![Monthly Downloads](https://pepy.tech/badge/thesis/month)](https://pepy.tech/project/thesis)
[![Twitter](https://img.shields.io/twitter/url/http/shields.io.svg?style=social&label=Twitter)](https://twitter.com/thesis)
-->

[![Project generated with PyScaffold](https://img.shields.io/badge/-PyScaffold-005CA0?logo=pyscaffold)](https://pyscaffold.org/)

#  Optimizing Mixed-Effect Models for Improved Performance and Interpretability

## Overview
This thesis investigates the effect of a large number of groups on mixed-effects models. When dealing with data with a large number of groups, not all the groups are unique and some groups might be similar to others, so combining them could improve the model performance. We conducted several experiments on synthetic data and found that reducing the number of groups improved the performance of existing mixed-effects models. We aimed to develop methods for group reduction that improve model performance as well as interpretability. However, our proposed methods were able to achieve better model performance but have a lack of interpretability in explaining why the groups were combined, which remains an area for further exploration and improvement in methods.

## Objectives
- To investigate the impact of a large number of groups on the performance of existing mixed-effects models.
- To develop group reduction methods to enhance model performance and interpretability.
- To apply these methods to both synthetic and real-world datasets to validate their effectiveness.

## Key Findings
- **Experiment-I:** Demonstrated that increasing the number of groups significantly degrades model performance.
- **Experiment-II:** Showed that strategic group reduction can substantially improve model performance.
- **Experiment-III:** Proposed group reduction methods significantly enhance model performance.


## Resources

- Code for Mixed Effects Models
     > ARMED https://gitfront.io/r/DeepLearningForPrecisionHealthLab/54f18307815dfb2148fbc2d14368c1268b63825e/ARMED-MixedEffectsDL/

     > LMMNN https://github.com/gsimchoni/lmmnn
     
     > MERF https://github.com/manifoldai/merf/tree/master

- Code for subgroup discovery and exceptional model mining
     http://www.ecmlpkdd2018.org/wp-content/uploads/2018/09/749.pdf)
     https://github.com/flemmerich/pysubgroup

- Literature on exceptional model mining
     https://wwwis.win.tue.nl/~wouter/Publ/W3-EMM_MTP.pdf

- [Slides](https://docs.google.com/presentation/d/1uIVstYVFzIe4RDEFKaanmnqZYlY-ZEH5NMFYDYqwb1k/edit?usp=sharing)

- [Documentation](https://www.overleaf.com/3329248876jkjghsyphzxv#1cb8df)

## Setup

We generally use [conda](https://docs.conda.io/en/latest/miniconda.html) and [Jupyter notebooks](https://jupyter.org/) for development.
To set up this project, do the following:

```bash
conda env create -f conda_environment.yml
```

<!-- pyscaffold-notes -->

## Note

This project has been set up using PyScaffold 4.4. For details and usage
information on PyScaffold see https://pyscaffold.org/.
