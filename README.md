# Image Prosessing

This repository contains implementations of basic image processing filtering techniques based on the frequency domain and the convolution theorem. In addition, the notebook *algorithms* includes implementations of several fundamental image processing algorithms.

### Containments

- *simple_image_processing.ipynb*:

Direct image processing such as grayscaling, color inverting and convolution. Results are found in "results".

<p align="center">
  <img src="images/duck.jpeg" width="45%" />
  <img src="results/sobel.png" width="45%" />
</p>

- *frequency-domain.ipynb*:

Filtering tequnics using the frequency domain. Playing around with the convolution theorem. I also create my own filters that filters a image with periodic noise. Results are found in "image_processed".

<p align="center">
  <img src="images/noisy_moon.png" width="45%" />
  <img src="image_processed/moon_filtered.png" width="45%" />
</p>

- *algorithms.ipynb*:

Implementation of algorithms used in image processing. 

<p align="center">
  <img src="images/blood-vessels.png" width="45%" />
  <img src="image_processed/blood-vessels-boundary.png" width="45%" />
</p>

### Academic context

The implementations in this repository is part of the tasks given to students in the course **TDT4195 Visual Computation Fundumentals (fall 2025)**. All images used is provided by the creator of these tasks.

Language: *English*

### Requirements

- Python 3.x
- "numpy"
- "scipy"
- "matplotlib"
- "scikit-image"
- "jupyterlab"
- "ipykernel"
- "pillow"
- "tqdm"
- "pandas"