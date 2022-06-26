# Messing about with Tensorflow

## Notes
1. *Installation* In addition to the packages mentioned, I had to install `python -m pip install torchvision matplotlib Ipython tensorboardX` 
1. *Code change* The normaliser in [gan.py] (gan.py)(line 12) had to be changed from ~~`transforms.Normalize((.5,.5,.5), (.5,.5,.5))`~~ to `transforms.Normalize((.5,), (.5,))` I assume that this has to do with me using newer libraries

## links
### Source of this code
* https://medium.com/ai-society/gans-from-scratch-1-a-deep-introduction-with-code-in-pytorch-and-tensorflow-cb03cdcdba0f
### Further reading / Inspiration
* https://towardsdatascience.com/five-gans-for-better-image-processing-fabab88b370b
* https://pyimagesearch.com/2021/12/13/gan-training-challenges-dcgan-for-color-images/
* https://www.tensorflow.org/hub/tutorials/image_enhancing
* https://www.tensorflow.org/hub/tutorials/boundless