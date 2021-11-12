# AINARI
Hackathon - UMHACKATHON 2021 - AINARI - A centralized system to monitor paddy field by using image classification method and data from IOT to predict possible upcoming disease with the help of Microsoft Azure.

Our team with a member of 5 people designed a centralized paddy field monitoring system to predict and detect possible diseases and risks.
![map](https://user-images.githubusercontent.com/65883921/135128461-4948a6da-e38a-4174-a0f3-a64dd7b134a1.png)
![dashboard](https://user-images.githubusercontent.com/65883921/135128473-741cb329-0d19-49d4-b7cd-db92ffffc6e2.png)

My role in the project is mainly to train and test the image classification and object detection model by using Azure Machine Learning Designer, AutoML and Custom Vision.
Therefore, there are less coding involved because Microsoft Azure Machine Learning is a collection of services and tools intended to help developers train and 
deploy machine learning models through its Azure public cloud.

However, we are also using **[Google Colab](https://colab.research.google.com/drive/1vkZQNxAoq5Va8CfmEQgL-lcOGdkBxbeC?usp=sharing)** to try out other model to compare the accuracy.
From what we get, the models in Azure perform better.

![designer3](https://user-images.githubusercontent.com/65883921/135126867-80b11d4e-5ecf-49ae-ae0d-26f1fe9c95e4.png)

This is how we arrange the flow of the data before deploy the model so that we can use it in our front end website.
![designer](https://user-images.githubusercontent.com/65883921/135126880-06648a5a-70c4-44c8-b6c3-daa52e8bef40.png)

The dummy data created are used here, to train the model with automl to predict possible risk that may happen 
based on Humidity, Water Level, Nitrogen, Phosphorus, Potassium, and Rainfall.
![automl](https://user-images.githubusercontent.com/65883921/135126929-bc12e5c6-9577-4673-8412-664cfffc06e5.png)

We use the object detection in Custom Vision to help us identify which part of the paddy is ill and the model performed fairly well.
![custom vision1](https://user-images.githubusercontent.com/65883921/135126938-07d2f6e1-311f-4707-a513-95a3eeffd939.png)
