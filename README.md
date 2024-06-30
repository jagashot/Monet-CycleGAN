
# CycleGAN Artistic Style Transfer Project

## Overview

This project leverages CycleGAN, a type of Generative Adversarial Network (GAN), to transform photographs into images that emulate the artistic style of Claude Monet. Our aim is to computationally capture and replicate the unique stylistic elements characteristic of Monet’s paintings, presenting a fascinating intersection of computer vision, deep learning, and fine arts.

## Notebooks

The project contains two main notebooks:

- **Test Notebook:** This notebook allows for organized evaluation of our models without print statements or other distractions. [Link to Test Notebook](https://colab.research.google.com/drive/1qTtgjT6qmVnX4rL26rb5o1N1JewkGsgb?usp=sharing)
- **Training Notebook:** This notebook includes all the comments, print statements, and previous experiments. [Link to Training Notebook](https://colab.research.google.com/drive/14xVer_CXjznn-sedlLXOvqIfiPrPfgR_?usp=sharing)

To run the notebooks, execute the cells sequentially. For convenience, we have added an option to upload an image at the bottom of the code cell. Run the cell and upload an image for testing. To check multiple images, re-run the specific cell to upload a new image.

## Project Details

### Dataset

We utilize a dataset comprising Claude Monet’s paintings, providing a rich collection of artistic styles and brushstrokes. This serves as the foundation for training our CycleGAN model.

### Objectives

The primary objective is to train a CycleGAN model capable of generating images that mimic Monet's distinctive style. This involves developing a generator model that learns to synthesize Monet-esque imagery, while a discriminator model evaluates the fidelity of the generated outputs.

### Experiments

1. **Base Model Training:** Initial training of the CycleGAN model to transform photographs into Monet-style paintings.
2. **Parameter Refinement:** Fine-tuning various parameters within the model to enhance image fidelity.
3. **Augmentations and Learning Rate Scheduler:** Incorporating data augmentation and a dynamic learning rate scheduler to improve model performance.
4. **Extended Training:** Extending training duration and implementing a learning rate scheduler for better optimization.

### Results

Our experiments show significant improvements over time, with the final model achieving high fidelity in generating Monet-style images. Detailed results and reflections on each experiment are provided within the project documentation.

## Methodology

Our approach draws inspiration from JIESHENDS2020's Kaggle notebook, adapting their strategies and optimizing hyperparameters specifically for Monet-style image generation. The training process focused on optimizing adversarial and cycle-consistency losses.

## Code

The source code for this project is available on Google Colab:

- [Train Notebook](https://colab.research.google.com/drive/14xVer_CXjznn-sedlLXOvqIfiPrPfgR_?usp=sharing)
- [Test Notebook](https://colab.research.google.com/drive/1qTtgjT6qmVnX4rL26rb5o1N1JewkGsgb?usp=sharing)

## Conclusion

This project underscores the transformative potential of deep learning in artistic style transfer. Through iterative refinement and interdisciplinary collaboration, we achieved remarkable results in generating Monet-style artwork, deepening our appreciation for the intersection of technology and art.
