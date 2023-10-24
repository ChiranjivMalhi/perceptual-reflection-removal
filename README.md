# Reflection-Removal

This code is based on tensorflow. It has been tested on Ubuntu 16.04 LTS.

## ![Our result compared against CEILNet on real images.](./teaser/teaser.png)


## Setup
  * Download [VGG-19](http://www.vlfeat.org/matconvnet/pretrained/#downloading-the-pre-trained-models). Search `imagenet-vgg-verydeep-19` in this page and download `imagenet-vgg-verydeep-19.mat`. We need the pre-trained VGG-19 model for our hypercolumn input and feature loss
  * Download pre-trained model [here](https://drive.google.com/open?id=1I9e2r_e0Ap6ds4MYRwoamUUlz6PzXPPj).
  * Move both the files into your Drive and name the folder reflection-dataset.
  * Go to Colab link https://colab.research.google.com/drive/1uCr9e3Dd8n3xzBVM7Oq1Y9RFFvlzRscB?usp=sharing
  * Run all the commands.

## Testing

* Change `test_path` (line 419) to your test image folder. If you want to test on the provided test images (e.g. in `./test_images/real/`), keep it as it is.
* test results can be found in `./test_results/`

Then, run

`$ python3 main.py --task pre-trained --is_training 0`


## Acknowledgement
Part of the code is based upon [FastImageProcessing](https://github.com/CQFIO/FastImageProcessing)

## Citation
If you find this work useful for your research, please cite:

```
@inproceedings{zhang2018single,
  title = {Single Image Reflection Separation with Perceptual Losses},
  author = {Zhang, Xuaner and Ng, Ren and Chen, Qifeng}
  booktitle = {IEEE Conference on Computer Vision and Pattern Recognition},
  year = {2018}
}
```

## Contact
Please contact me if there is any question (Cecilia Zhang <cecilia77@berkeley.edu>)

