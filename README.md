# Reflection-Removal

This code is based on tensorflow.

## ![Our result compared against CEILNet on real images.](./teaser/teaser.png)


## Setup
  * Download [VGG-19](http://www.vlfeat.org/matconvnet/pretrained/#downloading-the-pre-trained-models). Search `imagenet-vgg-verydeep-19` in this page and download `imagenet-vgg-verydeep-19.mat`. We need the pre-trained VGG-19 model for our hypercolumn input and feature loss
  * Download pre-trained model [here](https://drive.google.com/open?id=1I9e2r_e0Ap6ds4MYRwoamUUlz6PzXPPj).
  * Move both the files into your Drive and name the folder reflection-dataset.
  * Go to Colab link https://colab.research.google.com/drive/1uCr9e3Dd8n3xzBVM7Oq1Y9RFFvlzRscB?usp=sharing
  * Run all the commands.

## Testing

* If you want to test on the provided test images (e.g. in `./test_images/real/`), keep it as it is.
* If you want to test on your images upload the images in (e.g. in `./test_images/real/`) folder.
* Then run the last command on Colab again.
* Test results can be found in `./test_results/`


