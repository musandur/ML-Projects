# Documentation

The purpose of this README documentation is to guide any visitor through the different **Deep Learning**  tasks that I have so far implemented and uploaded here.
Broadly speaking, all the uploaded works address image-based prediction tasks by using **neural networks, convolutional neural networks and some computer vision frameworks.** 


In the followings, I will provide a quick describtion of each uploaded file and give a *url link* that, once clicked on, will directly lead to the content of the very work! Note also that these mini-projects were implemented on Google Colab notebook. I also used the integrated GPU in this notebook. It was free until at some point when I had to buy my own GPU pro :)


# Image Segmentation and detection
First of all, to perform image segmentation and image/object detection tasks, I have chosen to work with synthetic data. That is, I have create my own dataset that I have generated from some mathematical models that I had built in the past during some of academic research project. That is indeed very interesting, as it  exposed me to work on a dataset that is very different from the usual ones(dog/cats, MNIST, etc). Besides, I just felt like my academic research was helpful in the sense that I could use a part of it to perform some AI tasks.

 ## Object detection
In this work, I have use the MASK-RCNN framework to perform object detection in a custom dataset. Given the nature of my dataset, I have drawn a link to some potential biological application including single/multiple cell splitting scenarios. The mini-project can be viewed by clicking  [here](https://github.com/musandur/ML-Projects/blob/main/Object_Detection.ipynb) or copy and paste this (https://github.com/musandur/ML-Projects/blob/main/Object_Detection.ipynb)

## Instance and Semantic Segmentation

With the same synthetic dataset, I go forward to work on image segmentation tasks. That is, I separately implemented the two different segmaentations: Instance Segmentation and Semantic Segmentation. However, both segmentation tasks were implemented using the U-net (**encoder/decoder**) convolutional neural network and the **TensoFlow** framework.

* Instance Segmentation
The implementation and results can be found [here](https://github.com/musandur/ML-Projects/blob/main/Image_Segmentation_version1.ipynb) or copy and past the link (https://github.com/musandur/ML-Projects/blob/main/Image_Segmentation_version1.ipynb)

* Semantic Segmention
The implementation and results can be found [here](https://github.com/musandur/ML-Projects/blob/main/Instance_segmentation.ipynb) or copy and paste the link (https://github.com/musandur/ML-Projects/blob/main/Instance_segmentation.ipynb).

# Image classification and adversarial robustness
In this mini-project, I explored the field of adversarial robustness in image classification. Hence, I used the *(cat, dog)* dataset and the tensorflow Neural Structured Learning (NSL) framework to build robust classification models that can highly resist adversarial attacks. The implementation and results of this work can be found [here](https://github.com/musandur/ML-Projects/blob/main/Project1.ipynb) or copy and paste the link (https://github.com/musandur/ML-Projects/blob/main/Project1.ipynb)

# Image Classification and Model Explainability
* This is a Classification+ Explainability task: Classification using **ResNet50** and **Vgg16** CNN  and models Explainability using **LIME (Local Interpretable Model-agnostic Explanations)**.  Implementation and results can be found [here](https://github.com/musandur/ML-Projects/blob/main/Model_ResNet50_Vgg16_Explainability.ipynb) or copy and paste the link (https://github.com/musandur/ML-Projects/blob/main/Model_ResNet50_Vgg16_Explainability.ipynb).


* A code-oriented thought-provoking mini-work that states that counterfactual explanations could be used as adversarial samples to build an intuitive defense algorithm agaist adversarial attacks. This means combining model explainability techniques and counterfactuals explanations to generate adversarial images and ultimately build a defense algorithm. Work sample can be found [here](https://github.com/musandur/ML-Projects/blob/main/Project2.ipynb) or copy and paste this link (https://github.com/musandur/ML-Projects/blob/main/Project2.ipynb)
 





