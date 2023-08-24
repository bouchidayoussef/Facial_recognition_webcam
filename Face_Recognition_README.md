
# README for Face Recognition Program

---

## Introduction
This project focuses on recognizing faces using a deep learning model. It captures video feed from the webcam, detects faces in real-time, and identifies the person based on the trained model.

## Libraries and Tools Used
- Image processing: `cv2`
- Neural network and array handling: `numpy`, `tensorflow`, `keras`

## Model Architecture
- A pre-trained `ResNet50` model with weights from ImageNet was used as the base model.
- Additional layers, including convolutional, batch normalization, max pooling, global average pooling, dense, and dropout layers, were added to customize the model for the specific task.

## Data Preprocessing and Augmentation
- The data was loaded from the directory `'D:\face_recog\'`.
- Augmentation techniques, such as rescaling, rotation, width and height shifting, shearing, zooming, and horizontal flipping, were applied to the training images.

## Model Training
- The model was trained on the augmented data for 1000 epochs with a batch size of 32.

## Real-time Face Recognition
- The Haar cascade classifier was used for real-time face detection in the webcam feed.
- Faces detected in each frame were passed through the trained model to predict the person's identity.
- The identified person's name was displayed on the video feed.

## Conclusion
This project provides a solution for real-time face recognition using deep learning. It can be extended or modified for various applications, such as security, attendance systems, and more.

---

