# End_to_End_Deep_Learning_Project
Potato Disease Classification Project

This project bases on the below video series. I did this project while pursuing the instructions at the video series.
https://www.youtube.com/watch?v=dGtDTjYs3xc&list=PLeo1K3hjS3utJFNGyBpIvjWgSDY0eOE8S


This project is a comprehensive end-to-end deep learning project in the agriculture domain to help farmers detect diseases in potato plants using image classification. 
Let's break down the various components and technologies used in this project:

1) Model Building:
TensorFlow: This is the deep learning framework used for building the image classification model. TensorFlow provides a range of tools and libraries for building and training deep neural networks.
CNN (Convolutional Neural Network): CNNs are a class of deep learning models commonly used for image classification tasks. They are designed to automatically and adaptively learn patterns from data.
2) Data Augmentation: Data augmentation techniques are used to increase the diversity of the training dataset by applying transformations to the images, such as rotation, flipping, and scaling. This helps improve model generalization.
tf.dataset: tf.data is a TensorFlow API for building efficient and scalable input pipelines for data processing. It's used to load and preprocess the dataset for training.
Backend Server and ML Ops:
TensorFlow Serving: TensorFlow Serving is a system for serving machine learning models in production environments. It provides a simple and efficient way to deploy trained models as APIs.
3) FastAPI: FastAPI is a modern, fast (high-performance), web framework for building APIs with Python. It is used to create the backend server for serving the model predictions via API endpoints. FastAPI is chosen for its speed and ease of use.
4) Model Optimization:
Quantization: Model quantization is a technique to reduce the memory and computation requirements of deep learning models. It's especially useful for deploying models on resource-constrained devices.
TensorFlow Lite: TensorFlow Lite is a framework for deploying machine learning models on mobile and embedded devices. It allows you to optimize and run models on mobile devices efficiently.
5) Frontend:
React JS: React is a popular JavaScript library for building user interfaces. React JS is used for developing the web-based frontend of the project.
React Native: React Native is a framework for building mobile applications using React. It allows you to create a mobile app that can run on both iOS and Android platforms, sharing much of the codebase with the web frontend.
6) Deployment:
GCP (Google Cloud Platform): Google Cloud Platform is a cloud computing platform provided by Google. It's used for deploying and hosting various components of the project.
GCF (Google Cloud Functions): Google Cloud Functions is a serverless compute service that allows you to run single functions in response to HTTP requests. It can be used to trigger actions based on API requests from the frontend and backend.

The overall flow of the project involves training a CNN model on a dataset of potato plant images, integrating this model into a FastAPI backend for serving predictions, and building both web and mobile frontends to enable farmers to take pictures of potato plants, send them to the backend, and receive disease diagnosis results in real-time.

The model is optimized for deployment on mobile devices using TensorFlow Lite, and the whole system is hosted and scaled on Google Cloud Platform for reliability and scalability. This project aims to assist farmers in identifying diseases in potato plants, ultimately helping them reduce economic losses and crop waste.
