# Brain-Tumor-Detection

Application Architecture

• Frontend: HTML page (frontend.html) that allows users to upload an image for tumor detection.


• Backend: Flask application that:


o Receives image uploads.


o Preprocesses the image.



o Uses a trained CNN model (VGG16 + custom layers) to classify the tumor.


o Sends the prediction result and confidence back to the frontend.


• Model: A fine-tuned VGG16 model with transfer learning, trained on four classes – glioma, meningioma,
pituitary, notumor.


3.1.3.1 Dataset


• Source: https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset


The dataset was taken from Kaggle:


Title: Brain Tumor MRI Dataset


• Structure:


The data set is properly organized into two main directories: Training and Testing.


Each directory contains four subdirectories that correspond to various tumor categories: glioma, meningioma,
notumor, and pituitary.


• Categories (Designations)


There are 4 classes in total.


1. The glioma tumor is derived from the glial cells of the brain.


2. Meningioma Tumor – Composed of the meninges (spinal cord and brain membrane).


3. Pituitary Tumor – Found in the pituitary gland.


4. No Tumor – Normal MRI scans with no indication of tumors.

<img width="1305" height="598" alt="Screenshot 2025-04-14 at 2 31 02 PM" src="https://github.com/user-attachments/assets/b06805d0-c88e-4a79-9084-9f51631d9d2c" />




OUTPUT:

<img width="1440" height="900" alt="Screenshot 2025-04-16 at 1 40 04 AM" src="https://github.com/user-attachments/assets/4d4a33ec-4a71-4786-891a-72a78163dd40" />

<img width="1440" height="900" alt="Screenshot 2025-04-16 at 1 35 24 AM" src="https://github.com/user-attachments/assets/1fbeb897-ee40-412b-bc86-17e170d5a021" />



