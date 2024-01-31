Problem statement:
Farmers who grow potatoes and tomatoes face a lot of economic losses every year because of various diseases that can happen to these plants. There are two common diseases: early blight and late blight. Early blight is caused by fungas, and late blight is caused by a specific microorganism. If farmers can detect early and apply appropriate treatment, it can save a lot of waste and prevent economic loss.

Collected data and implemented data cleaning and preprocessing using the TF dataset and data augmentation strategies to enhance model training. Built and trained a CNN model with TensorFlow, achieving high accuracy in distinguishing between healthy, early blight, and late blight plant leaf conditions. Developed a FastAPI backend and built a React.js web interface that calls the FastAPI server upon uploading a plant leaf image; it then predicts and displays the label—whether it's healthy, early blight, or late blight. Deployed the model on the Google Cloud Platform using cloud functions to manage serverless operations and ensure seamless service availability.

For model building: Tensorflow, CNN (Convolutional Neural Network), data augmentation, TF dataset
Backend Server: FastAPI
Frontend: React.js
Deployment: GCP (Google Cloud Platform)
