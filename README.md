# Image Prosessing

This repository contains implementations of basic image processing filtering techniques based on the frequency domain and the convolution theorem. In addition, the notebook *algorithms* includes implementations of several fundamental image processing algorithms.

### Containments

- *simple_image_processing.ipynb*:

Direct image processing such as grayscaling, color inverting and convolution. Results are found in "results".

<p align="center">
  <img src="images/duck.jpeg" width="45%" />
  <img src="results/duck_sobel.png" width="45%" />
</p>

<p align="center">
  <em>Figure 1: Original image on the left. Convolved image with a sobel kernel on the right.</em>
</p>

- *frequency-domain.ipynb*:

Filtering techniques using the frequency domain. Playing around with the convolution theorem. I also create my own filters that filters a image with periodic noise. Results are found in "image_processed".

<p align="center">
  <img src="images/noisy_moon.png" width="45%" />
  <img src="image_processed/moon_filtered.png" width="45%" />
</p>

<p align="center">
  <em>Figure 2: Original image (left) and filtered image (right). The image was filtered using a custom frequency-domain filter designed to remove components within the same frequency range as the horizontal lines present in the original image.</em>
</p>

- *algorithms.ipynb*:

Implementation of algorithms used in image processing. 

<p align="center">
  <img src="images/blood-vessels.png" width="45%" />
  <img src="image_processed/blood-vessels-boundary.png" width="45%" />
</p>

<p align="center">
  <em>Figure 3: In the original image (left) we can se a binary image of blood vessels. In the right image I have used an algorithm extracting the boundary of the original image.</em>
</p>

<p align="center">
  <img src="images/thumbprint.png" width="45%" />
  <img src="image_processed/thumbprint-segmented.png" width="45%" />
</p>

<p align="center">
  <em>Figure 4: In the original image (left) we can se a grayscale image of a thumbprint. In the right image I have used Otsus thresholding algorithm to separate the background from the foreground.</em>
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