# Python Visual Similarity – Examples

Example Jupyter notebooks and helper utilities for the
[pyvisim](https://github.com/MechaCritter/Python-Visual-Similarity) library
(Python Visual Similarity).

The notebooks walk through the main features of `pyvisim`: feature extraction,
VLAD / Fisher Vector encoding, building pipelines, image clustering and
retrieval evaluation.

## Contents

- [`notebooks/`](notebooks/) – the example notebooks:
  - `getting_started.ipynb` – a quick introduction to the library.
  - `pipeline.ipynb` – chaining encoders into a single pipeline.
  - `vlad_and_fisher_with_vgg16_deep_features.ipynb` – VLAD & Fisher Vector on
    VGG16 deep features.
  - `clustering_images_using_vlad.ipynb` / `clustering_images_using_fv.ipynb` /
    `clustering_images_using_pipeline.ipynb` – clustering images with the
    different encoders.
  - `m_ap_and_top_k_accuracy.ipynb` – evaluating retrieval with mAP and
    top-k accuracy.
- [`pyvisim_examples/`](pyvisim_examples/) – plotting and clustering helper
  functions used by the notebooks.

## Installation

This project depends on [`pyvisim`](https://github.com/MechaCritter/Python-Visual-Similarity).
Install it together with the example helpers in editable mode:

```bash
# from the repository root
pip install -e .
```

If `pyvisim` is not yet published to PyPI, install it from its repository first,
for example:

```bash
pip install "pyvisim @ git+https://github.com/MechaCritter/Python-Visual-Similarity.git"
```

To install PyTorch with CUDA support, see the comment in
[`pyproject.toml`](pyproject.toml).

## Running the notebooks

```bash
jupyter notebook notebooks/
```

The notebooks import the shared helpers via `from pyvisim_examples.utils import ...`,
so make sure the package is installed (`pip install -e .`) before running them.
