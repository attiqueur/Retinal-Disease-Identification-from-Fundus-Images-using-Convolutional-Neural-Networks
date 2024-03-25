# Retinal Disease Identification from Fundus Images using Convolutional Neural Networks

In this project, I developed a **Convolutional Neural Network (CNN)** to classify retinal images into three categories: **diabetic retinopathy**, **glaucoma**, or **normal**. The model achieved an impressive accuracy of **89%**. To prepare the dataset, I performed several preprocessing steps, including **resizing the images**, **normalizing pixel values**, and applying **data augmentation techniques** such as random flips and rotations. The CNN architecture consisted of **convolutional layers**, **max-pooling layers**, and **dense layers**. For training, I utilized the **Adam optimizer** and **sparse categorical cross-entropy loss**. Overall, this project aimed to improve diagnostic accuracy for retinal diseases using deep learning techniques.

### Summary of the steps:

- Import necessary libraries
- Set up parameters
- Load the dataset
- Visualize some images from the dataset
- Split the dataset into training, validation, and test sets
- Preprocess the data
- Define data augmentation and preprocessing layers
- Build the CNN model
- Compile the model
- Train the model
- Evaluate the model
- Visualize training and validation metrics
- Make predictions on images
- Save the model
