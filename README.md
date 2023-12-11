# National Missing and Unidentified Person System
<img width="254" alt="Screen Shot 2023-10-26 at 4 05 29 PM (1)" src="https://namus.nij.ojp.gov/sites/g/files/xyckuh336/files/images/2021-03/namus-logo-color.png">


# The Problem 
In 2022, the number of missing person files in the United States equaled 546,568 cases. Around 90,000 a year are never found, that's almost 1 million people in the last decade. Around the world people that go missing are not always reported, so the real number is actually going to be more than what is really reported. With new technologies and more thought out ways more and more people are going missing due to the advances in soceity.

# Strategy and Implementation


# Data Deck
Our data deck is a curated collection of diverse datasets containing images and relevant information related to missing persons. The dataset includes:

- Facial images from various sources
- Location data
- Time-stamped images to track movement
- Additional contextual information

- Iterative Improvement: Iterative model improvement often involves refining datasets. By collecting additional data, removing noisy or irrelevant samples, or augmenting the dataset, the model's performance can be enhanced.
  
- Quality of Predictions: The quality and representativeness of the dataset directly impact the quality of predictions made by machine learning models. A comprehensive dataset helps the model generalize well to new, unseen data.

- A high-quality, well-curated dataset is essential for training accurate, unbiased, and reliable machine learning models. It serves as the foundation upon which models learn and make predictions, influencing their performance and real-world applicability.

<img width="666" alt="Screen Shot 2023-11-14 at 1 17 56 PM" src="https://static01.nyt.com/images/2017/10/24/business/24ITINERARIES1/24ITINERARIES1-superJumbo.jpg"> 
<img width="666" alt="Screen Shot 2023-11-14 at 1 17 56 PM" src="https://images.unsplash.com/photo-1461870083782-4d7b4f364728?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1yZWxhdGVkfDF8fHxlbnwwfHx8fHw%3D&w=1000&q=80">

[Data_Deck](https://docs.google.com/presentation/d/11RWUg8SSAv8bfvosryX_T8-DEtAEd4V6R-sD0cVQQB4/edit#slide=id.p)
# AlexNet Filters
AlexNet is a powerful convolutional neural network (CNN) that we use as a key component of our image recognition system. The AlexNet filter enables us to:

- Identify unique facial features
- Perform image classification
- Enhance image recognition accuracy

Key features of AlexNet include:

Deep Architecture: AlexNet consists of eight layers, including five convolutional layers followed by three fully connected layers. This depth was considered quite deep at the time of its introduction.

Rectified Linear Units (ReLU): AlexNet used the rectified linear unit activation function (ReLU) for the hidden layers. ReLU helps mitigate the vanishing gradient problem, allowing the model to converge faster during training.

Overlapping Pooling: Instead of traditional non-overlapping pooling layers, AlexNet employed overlapping pooling, where the pooling regions overlap, helping to capture more spatial hierarchies in the data.

Data Augmentation: To reduce overfitting and improve generalization, data augmentation techniques such as cropping and flipping were applied during training.

Dropout: Dropout, a regularization technique, was introduced in the fully connected layers to prevent overfitting by randomly dropping out units during training.

Local Response Normalization (LRN): LRN was used to provide local contrast normalization in the convolutional layers.

Large-Scale Training: AlexNet was trained on a large-scale dataset called ImageNet, which contained millions of labeled images across thousands of categories.

[Alexnet Filters](https://colab.research.google.com/drive/16yId_Y7fSr6D89m-uU-RbUlArJ8bUmRL?usp=sharing#scrollTo=WANJibeUNghZ)
# Pose
A pose machine, in the context of computer vision and machine learning, typically refers to a system or model designed to estimate the pose of an object or person in an image or video. Pose estimation involves determining the spatial positions of key points or joints on the object or person, capturing information about its position and orientation.
For example, in human pose estimation, a pose machine could be a model that identifies and tracks the positions of key body joints such as shoulders, elbows, hips, and knees.
<img width="666" alt="Screen Shot 2023-11-14 at 1 17 56 PM" src="https://mobidev.biz/wp-content/uploads/2020/07/2d-representation-albert-einstein-body-pose.jpg">

This information is valuable in finding key features for the person or people that are missing, using the different action recognition, and the different human-computer interactions that are availible.

Pose Machine models are effective in estimating human poses from images, providing valuable information about the body's positioning and movement, which finds applications across several domains.
# WandB
We integrate Weights & Biases (WandB) to streamline our model training and experimentation process. Key features of our WandB integration include:

- Real-time monitoring of model training metrics
- Experiment tracking for model comparison
- Collaborative sharing of experiment results
- Model versioning and reproducibility

WandB provides a suite of tools to monitor, compare, and visualize various aspects of the training process, making it easier to understand and optimize machine learning models.

<img width="903" alt="Screen Shot 2023-11-12 at 8 39 14 PM" src="https://github.com/trich9/Company-Design/assets/143112521/8f481160-59be-4075-9fdb-946e1edb4215">

# Feature Map
A feature map refers to the output of a layer in the network that corresponds to the presence of specific features or patterns in the input data. Each layer in a CNN consists of multiple filters or kernels, and the application of these filters to the input data results in the creation of feature maps.
<img width="903" alt="Screen Shot 2023-11-12 at 8 39 14 PM"[Feature map](https://colab.research.google.com/drive/11IJ27NHDdtqZASIkYMjCRH-39-Peaz3F?usp=sharing#scrollTo=mDMIqD-twIVd)>

# Contact 
Email- acymerman2019@fau.edu
