# UNet + K-Means City Semantic Segmentation

A PyTorch project that combines **UNet** for pixel-wise semantic segmentation with **K-Means clustering** for post-processing, aimed at urban scene understanding.

## Features
- UNet architecture for semantic segmentation
- K-Means clustering to refine segmentation boundaries
- Tailored for cityscape imagery

## Research Papers
- Ronneberger, O., Fischer, P., & Brox, T. (2015). [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)
- MacQueen, J. (1967). [Some Methods for Classification and Analysis of Multivariate Observations](https://projecteuclid.org/euclid.bsmsp/1183143727)

## Usage
1. Clone the repo:  
   `git clone https://github.com/demss233/unet-kmeans-city-semantic-segmentation-pytorch.git`  
   `cd unet-kmeans-city-semantic-segmentation-pytorch`
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Run the notebook:  
   `jupyter notebook unet-torch-semantic-segmentation-of-city-images.ipynb`
