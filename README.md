# MSDS686
The repository covers a SegNet that I put together using the CamVid data set for my course at Regis University.

There are three files in this repository as of the time of this writing:
KerasGan.ipynb - an attempt at creating a GAN to do segmentation on the camvid data set (doesn't really work)
SegNet.ipynb - a SegNet model with skip connections for the camvid data set (works ~80% accuracy)
SegNetNoConnect - a SegNet model without skip connections for the camvid data set (works ~ 65% accuracy)

If you would like to run these, there are some things that you will need first.

Data, which I got from here:
  https://github.com/mostafaizz/camvid
  
Some Helper functions which can be found here:
  https://github.com/0bserver07/Keras-SegNet-Basic/blob/master/helper.py
  
Once you get those things together, you will also need to set your paths.

Some of the results:

![alt text](https://github.com/DSNeville/MSDS686/blob/master/Results.png)
