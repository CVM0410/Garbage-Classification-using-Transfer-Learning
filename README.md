# Garbage-Classification-using-Transfer-Learning

Welcome to the GitHub repository for the Garbage Classification project using Transfer Learning. This project demonstrates the application of machine learning to enhance waste management systems by accurately classifying different types of waste using the EfficientNetV2S model, pre-trained on the ImageNet dataset.

## Project Overview
Effective waste management is crucial for environmental sustainability. This project addresses the challenge by applying advanced machine learning techniques to classify waste more accurately and efficiently. Using a transfer learning approach with the EfficientNetV2S model allows the system to perform high-accuracy classification even with limited data.

## Features
High Accuracy: Achieved a classification accuracy of 97.03%, significantly enhancing the capability to segregate different waste types.
Advanced Model: Utilizes EfficientNetV2S, known for its efficiency and effectiveness in handling diverse image processing tasks.
Robust Dataset Handling: Includes preprocessing steps such as resizing, normalization, and augmentation to prepare the data for training.

## Deployment

This project utilizes Flask to create a RESTful API for the Garbage Classification application, allowing users to interact with the model through HTTP requests. The API accepts image files, processes them using the EfficientNetV2S model, and returns the predicted classification of the waste type.

### Hosting on Hugging Face Spaces

The application is hosted on Hugging Face Spaces, providing an accessible and interactive user interface where users can upload images and receive immediate classification results. Hugging Face Spaces simplifies the deployment process, automatically handles the infrastructure, and scales seamlessly to accommodate the number of users.

### Access the Application

To use the application, visit the following URL:
[Garbage Classification on Hugging Face Spaces](https://huggingface.co/spaces/chirag0410/garbage_classification)

### How to Use

1. **Visit the Link**: Click on the link above to access the web interface.
2. **Upload an Image**: Use the upload button to select an image of waste from your device. The image should be clear and focused on the item you wish to classify.
3. **Get Classification Results**: After uploading the image, the model will process it and display the classification label along with the confidence level of the prediction.

### Technical Details

The Flask API is containerized using Docker, ensuring that the application can be easily deployed and run in any environment supported by Hugging Face Spaces. The API receives image data, preprocesses it according to the requirements of the EfficientNetV2S model, and computes the prediction which is then sent back as a response to the user.

This deployment strategy ensures that the model is both scalable and robust, capable of handling multiple requests simultaneously without degradation in performance.

For more detailed technical insights or to report issues, you can explore the repository or open an issue to discuss potential improvements and feedback.


