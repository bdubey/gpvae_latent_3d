# GPVAE for Latent Dynamics from Pixels in 3 Dimensional Video
## Report
Report: https://github.com/bdubey/ml_project_gpvae/blob/master/report/GPVAE3D_REPORT.pdf

In this project we try to learn latent dynamics of pixels from videos in three dimension
using Gaussian Prior to standard Variational Autoencoder.

This work is extended from similar work for 2d images in paper:
[Gaussian Process Prior VAE for Latent Dynamics from Pixels](http://proceedings.mlr.press/v118/pearce20a/pearce20a.pdf)

Initially forked from https://github.com/scrambledpie/GPVAE

Written in Tensorflow 1.13, python 3.7.

## Data
3D trajectory of 30 points (x,y,z) generated by GP and each point is converted to ball of radius 2
#### Moving Ball:  Moving ball in 16 size cube
![Training GP-VAE](https://github.com/bdubey/ml_project_gpvae/blob/master/result_projection2.png)
## Result
### Reconstruction of trajectory on some samples not used in training
#### Result 1:  16x16x16 samples and there reconstruction
![Training GP-VAE](https://github.com/bdubey/ml_project_gpvae/blob/master/result_final.png)
#### Result 2:  16x16x16 samples and there reconstruction
![Training GP-VAE](https://github.com/bdubey/ml_project_gpvae/blob/master/result_final2.png)

