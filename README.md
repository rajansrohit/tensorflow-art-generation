# Tensorflow-Art-Generation

A python script that utilizes the VGG19 pre-trained model to transfer style of famous paintings to your images/photos.

Download "imagenet-vgg-verydeep-19" from http://vlfeat.org/matconvnet/pretrained/ and place into "pre_trained_model" folder

# Prerequisites
1. Tensorflow Library
2. numpy, scipy, Pillow, matplotlib
3. VGG file

# Basic Use
```
python run_main.py --content <content file> --style <style file> --output <output file>
```

