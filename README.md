# Bangkit Assessment
A repository for Google Bangkit first Online Assessment

## Team
[Arief Hirmanto](https://github.com/ariefhirmanto)  |      [Dimas Apeco Putra](https://github.com/dispectra) | [Gusti Triandi Winata](https://github.com/sanggusti)
------------------------------------------------------

## Topic
Covid-19 Chest X-Ray Classification ([dimas_notebook.ipynb](dimas_notebook.ipynb) and [arief_notebook.ipynb](arief_notebook.ipynb)) and U-Net Medical Image Segmentation Approach ([gusti_notebook.ipynb](gusti_notebook.ipynb))

## Problem Framing

## Approach
For X-Ray Chest Image Classification we use transfer learning of VGG16 and edit the last layer and train it with the Sansten Covid-19 Dataset.

For U-Net we approach with reference of the [paper](https://arxiv.org/abs/1505.04597), preprocess the data of Data Science Bowl 2018, Nucleus Dataset, build the architecture with reference to the paper, design the IoU relations and train the model.

## Result
For Chest X-Ray Classification we get results:

For U-Net Image Segmentation we got results:

## Conclusion
For Chest X-Ray Classification the model works

For U-Net Image Segmentation the model works

## Citation
- Adrian Rosebrock, [Detecting COVID-19 in X-ray images with Keras, TensorFlow, and Deep Learning](https://www.pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/)
- Rajeev Courses of Deep Learning and Computer Vision, Udemy, Chapter 19 Medical Image Segmentation
- Kjetil Åmdal-SævikKeras who made the [U-Net starter - LB 0.277](https://www.kaggle.com/keegil/keras-u-net-starter-lb-0-277)
- Jae Duk-Seo [Article](https://medium.com/@SeoJaeDuk/medical-image-segmentation-part-1-unet-convolutional-networks-with-interactive-code-d07231eb29bf) about U-Net