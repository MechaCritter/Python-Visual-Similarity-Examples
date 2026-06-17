# Python Visual Similarity: Examples

Example Jupyter notebooks for the
[pyvisim](https://github.com/MechaCritter/Python-Visual-Similarity) library
(Python Visual Similarity).

The notebooks walk through the main features of `pyvisim`: feature extraction,
VLAD / Fisher Vector encoding, building pipelines, image clustering and
retrieval evaluation.

## Contents

- [`notebooks/`](notebooks/): the example notebooks:
  - `getting_started.ipynb`: a quick introduction to the library.
  - `pipeline.ipynb`: chaining encoders into a single pipeline.
  - `vlad_and_fisher_with_vgg16_deep_features.ipynb`: VLAD & Fisher Vector on
    VGG16 deep features.
  - `clustering_images_using_vlad.ipynb` / `clustering_images_using_fv.ipynb` /
    `clustering_images_using_pipeline.ipynb`: clustering images with the
    different encoders.
  - `m_ap_and_top_k_accuracy.ipynb`: evaluating retrieval with mAP and
    top-k accuracy.
- [`pyvisim_examples/`](pyvisim_examples/): plotting and clustering helper
  functions used by the notebooks.

## Installation

Install the Pyvisim library and the dependencies for the examples:

```bash
uv pip install .
```

## Visit the [notebooks](notebooks/)

There are notebooks for different use-cases of this project. If you would like to 
suggest additional examples, feel free to contribute!

## Get in Touch
If you have any questions or just want to say hi, feel free to:
- Open an issue on [GitHub](https://github.com/MechaCritter/similarity_metrics_of_images/issues).
- Write me an email at [vunhathuy234@gmail.com](mailto:vunhathuy234@gmail.com).
- Connect on [LinkedIn](https://www.linkedin.com/in/nhat-huy-vu-80495111b/) to follow my work and share your thoughts.

## License
This project is licensed under the terms of the MIT license.