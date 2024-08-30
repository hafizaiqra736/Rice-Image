🍚 Rice Image Classification Project
Image Processing and Classification of Rice Varieties Using Machine Learning & OpenCV
This project focuses on classifying rice images into five varieties (Arborio, Basmati, Ipsala, Jasmine, Karacadag) using machine learning and deep learning techniques. Additionally, I employed image preprocessing techniques such as resizing, blurring, and zooming with OpenCV and Matplotlib for visualization.

📋 Project Overview
In this project, I implemented a CNN (Convolutional Neural Network) to classify rice images from the Rice Image Dataset using TensorFlow and Keras. Along with training the model, various image processing tasks such as resizing, blurring, and zooming were performed using OpenCV.

🚀 Key Steps
1. Data Preprocessing:
Image Extraction: The dataset was extracted from a zip file using the zipfile library.
Image Augmentation: Implemented data augmentation techniques including zooming, horizontal flip, and shear to enhance model training.
2. CNN Model Implementation:
Model Architecture: A sequential CNN was built with layers of Conv2D, MaxPooling2D, Dropout, and Dense layers to classify rice images into five categories.
Training: The model was trained on the preprocessed images using categorical cross-entropy and evaluated on classification accuracy.
3. Image Processing with OpenCV:
Reading & Displaying Images: Used OpenCV to read, display, and manipulate the images.
Resizing: Images were resized to specific dimensions for uniformity.
Blurring: Applied Gaussian blur to smooth the images.
Zooming: Performed zoom transformations using OpenCV’s rotation matrix to simulate a zoom effect.
Grayscale Conversion: Converted images to grayscale for additional analysis.
4. Visualization:
Matplotlib: Displayed the processed images including resized, zoomed, blurred, and original images using Matplotlib for comparison and inspection.
📊 Results
CNN Model: Successfully classified rice varieties with high accuracy using TensorFlow and Keras.
OpenCV Processing: Demonstrated effective image manipulations including resizing, blurring, and zooming for enhanced image analysis.
🏆 Conclusion
This project effectively showcases the combination of machine learning with image processing techniques for rice classification. The CNN architecture, along with various image transformations using OpenCV, provided meaningful insights into rice variety identification. The project emphasizes the importance of preprocessing and visualization when working with image data.
