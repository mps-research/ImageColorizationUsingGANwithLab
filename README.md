# ImageColorizationUsingGANwithL\*a\*b

A PyTorch implementation of "Image colorization using GAN" with L\*a\*b color space.

## Related Papers

Kamyar Nazeri, Eric Ng and Mehran Ebrahimi:
Image Colorization with Generative Adversarial Networks.
https://arxiv.org/pdf/1803.05400.pdf

Richard Zhang, Phillip Isola and Alexei A. Efros: 
Colorful Image Colorization.
https://arxiv.org/pdf/1603.08511.pdf

## Related Websites

[Image Colorization with U-Net and GAN Tutorial](https://colab.research.google.com/github/moein-shariatnia/Deep-Learning/blob/main/Image%20Colorization%20Tutorial/Image%20Colorization%20with%20U-Net%20and%20GAN%20Tutorial.ipynb#scrollTo=s2XbKE3hAJ8w)

## Training

1. Clone this repository and move to the directory.

```shell
% clone https://github.com/mps-research/ImageColorizationUsingGANwithLab.git
% cd ImageColorizationUsingGANwithLab
```

2. Download "places365standard_easyformat.tar" from [Places365 Dataset web page](http://places2.csail.mit.edu/index.html).

3. Put the tar into the data directory and extract files.

```shell
% cd data
% tar xvf places365standard_easyformat.tar
```

4. At the repository root directory, build "icganlab" docker image and run the image inside of a container.

```shell
% docker build -t icganlab .
% ./train.sh
```

## Checking Training Results

At the repository root directory, execute the following command.

```shell
% ./run_tensorboard.sh
```
