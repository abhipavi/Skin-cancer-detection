# Skin Cancer Detection using Deep Learning

## Abstract
This project focuses on developing a deep learning model for the detection of skin cancer, a dangerous and prevalent disease with alarming global statistics. Early detection of skin cancer is crucial for improving survival rates, which are significantly higher when diagnosed early. The paper addresses the need for early diagnosis with improved accuracy through the use of deep learning techniques.

## Introduction
The diagnosis of skin cancer at an early stage is vital for effective treatment and improved survival rates. Extensive research has been conducted in the field of computer image analysis algorithms to facilitate speedy and accurate diagnosis. Traditional methods often rely on normally distributed data, which may not accurately represent real-world scenarios. This paper proposes the use of nonparametric solutions, particularly deep learning, to assist dermatologists in diagnosing skin cancer by analyzing dermal images.

### Problem Definition
Traditional methods of skin cancer detection often require data to be normally distributed, which may not be feasible in real-world scenarios. Nonparametric solutions, such as deep learning, offer greater flexibility and accuracy in diagnosing skin cancer.

### Previous Work
Previous research by Mohammed Ali Kadampur and Sulaiman Al Riyaee introduced a deep learning-based model for skin cancer detection. While their approach offered ease of model construction, it was limited by software constraints.

### Motivation
The primary motivation behind this project is to enable early detection of skin cancer, thereby providing individuals with timely access to healthcare and reducing mortality rates associated with the disease.

### Overview
This paper outlines the development of a deep learning model using Python, TensorFlow, and the Keras API. Two approaches are employed: a hard-coded convolutional neural network (CNN) approach and a transfer learning approach. The HAM10000 dataset is used for training the models.

## Training
The models are trained using the Adam optimizer, categorical cross-entropy as the loss function, and accuracy as the metric. The CNN approach achieves an accuracy of 67.74% on training data, 68.45% on validation data, and 65.46% on test data. In comparison, the transfer learning approach with the EfficientNet-B0 architecture achieves higher accuracy scores: 89.89% on training data, 69.66% on validation data, and 72.39% on test data.

## Conclusion
The results indicate that the transfer learning approach using the EfficientNet-B0 architecture outperforms the hard-coded CNN approach in terms of accuracy and metric scores. Future work may involve employing other transfer learning approaches, such as ResNet models, to further improve accuracy and develop deeper models.

