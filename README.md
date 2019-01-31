# Toy Experiment for modifying DPED

## 1. What is DPED?

DPED is "DSLR-Quality Photos on Mobile Devices with Deep Convolutional Networks".

- Paper:[[paper]](https://arxiv.org/pdf/1704.02470.pdf) [[project webpage]](http://dped-photos.vision.ee.ethz.ch) 
- Repo:[DPED](https://github.com/aiff22/DPED)

In a word, it turns a poor phone-quality photo to a DSLR-quality photo with GAN network and other technologies.

## 2. What I've tried to modify?

- The comparison between **batch-normalization** and instance-normalization.
- Two generator: **Densenet** and Resnet.
- Paired training to Unpaired training based on Cycle GAN network.(By introducing cycle loss.)

## 3. Some results

Tips: For the limitation of time and ability, we doesn't focus on the results(two index: psnr&ssim). This is just a toy experiment.  :)

More details are recored in the [report](assets/report.pdf)

Keywords: GAN, Cycle GAN, Densenet, Resnet, Batch-norm, Instance-norm, Tensorflow.

1. Loss

   ![loss](assets\1.png)

2. Visual improvement(iteration 1000 and iteration 19000)

   ![loss](assets\2.png)

   ![loss](assets\3.png)

