# BME 404 Lab 03 — interactive tools

Two browser tools built while working through Lab 03 (MRI brain scan: segmentation
and volume visualization) of BME 404, Medical Imaging Sessional, BUET.

| | |
|---|---|
| **[Morphology Stepper](https://aranya016.github.io/Morphology-IPT/)** | Step a structuring element across a matrix one cell at a time and watch `imerode`, `imdilate`, `imopen` and `imclose` decide each output value. Editable matrix and stencil, grayscale mode, live MATLAB output. |
| **[Flip and Permute](https://aranya016.github.io/Morphology-IPT/flip-and-permute.html)** | The real `mriBrainPartition` volume from Series 8, downsampled exactly as `e7.m` does it. Apply `flip` and `permute` and watch which anatomical axis ends up on the vertical plot axis. |

Both are single self-contained HTML files — no build step, no dependencies.
Open them locally by double-clicking, or serve the folder with any static host.

Deployed from this repo by the GitHub Pages workflow in `.github/workflows/static.yml`.
