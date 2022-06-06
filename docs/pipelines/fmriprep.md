---
layout: default
title: fMRIPrep
parent: Pipelines
has_toc: true
---

# fMRIPrep

_fMRIPrep_ is a functional magnetic resonance imaging (fMRI) data preprocessing pipeline that is designed to provide an easily accessible, state-of-the-art interface that is robust to variations in scan acquisition protocols and that requires minimal user input, while providing easily interpretable and comprehensive error and output reporting. It performs basic processing steps (coregistration, normalization, unwarping, noise component extraction, segmentation, skullstripping etc.) providing outputs that can be easily submitted to a variety of group level analyses, including task-based or resting-state fMRI, graph theory measures, surface or volume-based statistics, etc.

All datasets in the RBC were preprocessed with fMRIPrep version #TODO. In the case that BOLD data was not available, fMRIPrep was run only on anatomical data with the `--anat-only` flag.

To learn more about fMRIPrep, follow [this link](https://fmriprep.org/en/stable/index.html) for their documentation, and [this link]() to read the Nature Methods publication.

```
@misc{esteban_oscar_2017_996169,
  author       = {Esteban, Oscar and
                  Blair, Ross and
                  Markiewicz, Christopher J. and
                  Berleant, Shoshana L. and
                  Moodie, Craig and
                  Ma, Feilong and
                  Isik, Ayse Ilkay and
                  Erramuzpe, Asier and
                  Goncalves, Mathias and
                  Poldrack, Russell A. and
                  Gorgolewski, Krzysztof J.},
  title        = {poldracklab/fmriprep: 1.0.0-rc5},
  month        = sep,
  year         = 2017,
  doi          = {10.5281/zenodo.996169},
  url          = {https://doi.org/10.5281/zenodo.996169}
}
```

