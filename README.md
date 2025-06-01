# Generating Monet-style images using CycleGAN

This project is based on a Kaggle competition: [I’m Something of a Painter Myself](https://www.kaggle.com/competitions/gan-getting-started)

The goal of this project is to generate Monet-style images from regular photos. I will build a model for this task using a special variant of GAN - the CycleGAN, which is particularly usefull for style-transfer tasks like this one. CycleGAN uses two generators and two discriminators to learn the mapping between two different image styles (in this case, regular photos and monet-style images). It uses the cycle-consistency loss to ensure that the generated images can be converted back to their original style, which is usefull as we don't have paired training data (monet pictures do not have the corresponding original photos obviously).

### 2. Data
The data for this project consists of two sets of images: regular photos (photo_jpg folder) and monet-style images (monet_jpg folder). Due to space constraints, I did not include all the images in this repo. You can find the entire sets on Kaggle competition page

----
*The score for this project can only be received after submitting the Notebook to Kaggle competition. Therefore, this Notebook is intended to run in Kaggle, using corresponding input and output folders.*
