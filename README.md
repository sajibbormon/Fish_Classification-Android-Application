
# 🐟 Fish Classification Android Application

An Android application that classifies fish images using a trained TensorFlow Lite model. Users can capture fish images directly using their device camera or select images from the gallery. Before classification, the application removes the image background and replaces it with a white background to focus on the fish.

## ✨ Features

- **Fish Classification:** Classifies fish images using a trained TensorFlow Lite model.
- **Camera Capture:** Capture fish images directly using the device camera.
- **Gallery Selection:** Select existing fish images from the device gallery.
- **Background Removal:** Automatically removes the background and keeps the fish object with a white background.
- **Classification Results:** Displays the predicted fish category after image processing.
- **Easy-to-Use Interface:** Simple and user-friendly application interface.
- **Real-World Testing:** Supports fish image classification using both gallery images and camera captures.

## 📱 Application Workflow

The following screenshots demonstrate how the application works, from opening the app to obtaining the classification result.

### 1. Application Home Screen

The home screen provides the main options for using the application.

![Application Home Screen](assets/1.jpg)

### 2. Selecting an Image

Users can select a fish image from their device gallery.

![Selecting Fish Image](assets/2.jpg)

### 3. Selected Fish Image

After selecting an image, the application displays the selected fish image before background removal.

![Selected Fish Image](assets/3.jpg)

### 4. Background Removal

The application removes the unwanted background and replaces it with a white background, keeping the fish object for classification.

![Background Removed Image](assets/4.jpg)

### 5. Fish Classification Result

After background removal, the processed image is passed to the trained TensorFlow Lite model, and the application displays the predicted fish category.

![Fish Classification Result](assets/5.jpg)

## 🎥 Real-World Application Demonstrations

The following videos demonstrate the application in real-world scenarios.

### 1. Fish Classification Using Gallery Images

This video demonstrates selecting fish images taken at a local market from the device gallery and classifying them using the application.

[▶️ Watch Gallery-Based Fish Classification Demo](https://drive.google.com/file/d/VIDEO_FILE_ID_1/view)

### 2. Fish Classification Using Camera

This video demonstrates capturing fish images directly at a local market using the device camera and classifying them with the application.

[▶️ Watch Camera-Based Fish Classification Demo]([https://drive.google.com/file/d/VIDEO_FILE_ID_2/view](https://drive.google.com/file/d/12i4N9xYddJYF7TyNG7IumaDtxD7mCiB2/view?usp=sharing))

> **Note:** Replace `VIDEO_FILE_ID_1` and `VIDEO_FILE_ID_2` with your actual Google Drive video file IDs. Make sure both videos have sharing access set to **Anyone with the link – Viewer**.

## ⚙️ How the Application Works

The application follows these steps to classify a fish image:

1. **Image Input:** The user captures an image using the camera or selects one from the gallery.
2. **Image Segmentation:** The application processes the image to separate the fish from its background.
3. **Background Replacement:** The unwanted background is removed and replaced with white.
4. **Image Classification:** The processed image is passed to the trained TensorFlow Lite classification model.
5. **Result Display:** The application displays the predicted fish category.

### Application Workflow

```text
       Camera / Gallery
              |
              v
        Input Image
              |
              v
      Fish Segmentation
              |
              v
      Background Removal
              |
              v
       White Background
              |
              v
    TensorFlow Lite Model
              |
              v
      Classification
              |
              v
       Display Result
```

## 🛠️ Technologies Used

- **Programming Language:** Java
- **Development Environment:** Android Studio
- **Machine Learning Framework:** TensorFlow Lite
- **Image Processing:** Android Bitmap Processing
- **Deep Learning:** Image Classification and Image Segmentation
- **Platform:** Android

## 📂 

```text
FishClassification/
│
├── app/
│   └── src/
│       └── main/
│           ├── assets/
│           │   └── fish_model.tflite
│           │
│           ├── java/
│           │   └── com/fishclassification/
│           │
│           └── res/
│
├── assets/
│   ├── 1.jpg
│   ├── 2.jpg
│   ├── 3.jpg
│   ├── 4.jpg
│   └── 5.jpg
│
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Android Studio
- Android device or emulator
- Android SDK
- Java development environment

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
   ```

2. Open the project in Android Studio.

3. Wait for Gradle synchronization to complete.

4. Connect an Android device or start an emulator.

5. Run the application.

## 🎯 Project Objective

The main objective of this project is to develop an Android-based fish classification application that makes fish identification easier through image processing and deep learning. By combining background removal with TensorFlow Lite image classification, the application aims to improve the focus on fish objects and provide a convenient way to classify fish images in real-world environments.

## 👨‍💻 Developer

**SAJIB BORMON**

Bachelor of Science in Computer Science and Engineering  
Daffodil International University

---

⭐ If you find this project interesting, please consider giving this repository a star!
