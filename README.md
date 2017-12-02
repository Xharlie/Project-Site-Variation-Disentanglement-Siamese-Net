# Project-Site-Variation-Disentanglement-Siamese-Net
This is a onging research. 
## 1. Introduction:
The purpose of this research is to design a semi-supervised network that disentangles the label-related and non-label related(variance) representation of a manifold. The label related representation denotes F_i which only has label related information(such as identity of human face). Another representation F_v contains all non-label information(such as illumination, pose and background information etc.)
The F_i and F_v are very usful in:
> Recognition or Clustering task such as:</br>
* Pose, illumination, etc. Invariance Face recognition.</br>
* Cross-Domain recognition</br>
* Better clustering result in dataset with large variance.</br>
</br>

> Variance Transformation</br>
* Stitching F_i and F_v from different images, we can transfer many appearance attributes (style, background, pose, etc.) in one image to another.

## 2. Task Formulation:
>![Image of Formulation](https://github.com/Xharlie/Project-Site-Variation-Disentanglement-Siamese-Net/blob/master/site-content/formulation/formulation.png)</br>

## 3. Model:
>![Image of Model](https://github.com/Xharlie/Project-Site-Variation-Disentanglement-Siamese-Net/blob/master/site-content/model/model.png)</br>

## 3. Clustering of F_i and F_v on MNIST:
>![Image of Model](https://github.com/Xharlie/Project-Site-Variation-Disentanglement-Siamese-Net/blob/master/site-content/clustering/clustering.png)</br>

## 4. Reconstruction(two image of same digit) and Cross Stitching(two image of different digit) Result on MNIST:
>![Image of Model](https://github.com/Xharlie/Project-Site-Variation-Disentanglement-Siamese-Net/blob/master/site-content/reconstruction/reconstruction.png)</br>

## 4. Latent Space Interpolation Result on MNIST:
>![Image of Model](https://github.com/Xharlie/Project-Site-Variation-Disentanglement-Siamese-Net/blob/master/site-content/reconstruction/interpolation.png)</br>
