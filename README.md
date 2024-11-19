# Skin Cancer Detection Using CNN
> A deep learning-based project aimed at building a Convolutional Neural Network (CNN) model to detect melanoma and other types of skin cancer. The project uses image data to help automate the early detection of skin cancer, which could potentially save lives through timely diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- This project focuses on developing a **Convolutional Neural Network (CNN)** to detect **skin cancer** using a dataset of images provided by the **International Skin Imaging Collaboration (ISIC)**.
- The business problem addressed here is the **early and accurate detection of melanoma**, which is crucial for successful treatment and potentially saving lives. Melanoma accounts for a high percentage of skin cancer-related deaths.
- The **dataset** used in this project is the **"Skin Cancer ISIC The International Skin Imaging Collaboration"** dataset, which consists of images from various classes of skin cancer.

## Conclusions
- The **Baseline Model** showed high training accuracy but low and fluctuating validation accuracy, indicating significant **overfitting**.
- Incorporating **data augmentation** and **dropout** in **Model 2** resulted in reduced overfitting and better alignment between training and validation accuracy, although the performance still needed improvement.
- The **Final Optimized Model** showed the best performance, with balanced dataset handling, early stopping, and improved dropout. This led to much better generalization, achieving high validation accuracy.
- The use of data augmentation, **balanced datasets**, and regularization techniques greatly **improved the model's generalization capabilities**, reducing overfitting and enhancing prediction quality.

## Technologies Used
- **Python** - version 3.10
- **TensorFlow** - version 2.12.0
- **Keras** (included in TensorFlow) - version 2.12.0
- **Matplotlib** - version 3.7.1
- **Pandas** - version 1.4.0
- **Numpy** - version 1.22.0
- **Augmentor** - version 0.2.10

## Acknowledgements
- This project was inspired by the need for early detection of **melanoma** to potentially reduce fatalities caused by skin cancer.
- The dataset was provided by **ISIC - The International Skin Imaging Collaboration**.
- The project is based on principles learned from CNN and Tensorflow modules in upGrad.

## Contact
Created by [@geekyabinash] - feel free to contact me!

