# Source code for single-label image classificaiton models

We are going to show the steps to run the experiments in batch.
You can feed the input to the model one by one, but it is not effective.


## Step 0: Dependencies
1. [EvalDNN](https://github.com/yqtianust/EvalDNN)
2. opencv-python for image processing, use `pip3 install opencv-python`


## Step 1: Download ImageNet Validation Set

You can find the instruction from imagenet website.

We need both the image and the annotations (xml file).

We assume the image is in `./img/org` and the xml file is in `./val2012_xml`

## Mutate the image

Run the `mutate_img.py` 


## Feed the inputs to models

Run the `run_keras.py`

## Analyze the data

Code will be updated later. 

