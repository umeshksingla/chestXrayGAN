### Learning to generate Chest X-Ray Images from sample data


We use an existing implementation of deep convolutional GAN in [pytorch](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html) to learn and generate chest X-Ray images directly. 
The dataset includes combined 5216 images of healthy people chest X-Rays and that of people with pneumonia.
Later we also calculate the Inception score and FID score of the generated images. 

It is only a proof-of-concept exercise and is in no way fine-tuned.
