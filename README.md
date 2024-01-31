# Image-restoration

Image restoration is a key activity in image processing that aims to recover the original quality of images that have been distorted by causes such as noise, blur, or other flaws. Image restoration approaches have seen considerable gains in terms of accuracy and efficiency as a result of recent advances in deep learning, notably convolutional neural networks (CNNs).

We devise an approach to address the damage in the image. These flaws include blurring and noise. The most prevalent problems that can occur in most settings are blur and noise. Several ways have been developed to fix any damage that may occur in the image. One of the most well-known ways is to employ deep learning techniques learned to remove blur, noise in photos, and add colour to black-and-white images; the technology has evolved through time. Image quality has steadily increased over time. The layers of a convolutional neural network (CNN) are convolutional, activation, and pooling.

![image](https://github.com/pratikpathe/Image-restoration/assets/99345342/d4f1ee1d-0b0d-442e-a666-d824229dc351)

**DATASET**
The DIV2K dataset is broken into the following sections:

Train data: We extract similar low resolution images from 700 high definition high resolution photographs and give both high and low resolution images for downscaling factors of 2, 3, and 4.
Data for validation: The low quality photographs are made available at the start of the challenge in order for participants to obtain online feedback from the validation server; the high resolution images will be made available when the challenge's final phase begins.

Test data: When the final evaluation phase begins, the participants will receive the low quality photographs, and the results will be revealed once the challenge is concluded and the winners are determined.
Context The dataset was produced to test the blur detection method. The dataset might be used to evaluate picture deblurring methods. As a result, while CNN and U-net cannot distinguish between fuzzy and clear images, high-quality photographs may be used for visual comparison.


**Implementation and modelling**

Step-1: import all the necessary libraries and download the dataset 

Step-2: Data Preparation

Step-3: The Input Image

Step-4: Generating Patches

Step-5: model configuration phase

Step-6: Training the model

Step-7: Modal Accuracy and Validation loss plot

Step-8: Prediction


**Conclusion**

We employed deep learning techniques, notably the U-Net model, to fix picture faults such as noise, blurring, and low resolution. The restoration accuracy varied from 85% to 90% after intensive training. The U-Net design effectively gathered both low-level and high-level information while preserving critical spatial features via skip connections. 

