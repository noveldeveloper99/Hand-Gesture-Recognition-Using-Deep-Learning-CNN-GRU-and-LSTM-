# Data-Mining-and-Machine-Learning-2
Semester Project repository

# Hand Gesture Recognition Using Deep Learning 

Hand gestures - a form of non-verbal communication, are now being utilized in developing various Human-Computer Interaction tools such as systems for communicating with deaf-mute people, robot controls, home automation devices and, medical devices. Hand Gesture Recognition systems find their immense application in a wide range of domains which include or may incorporate automated gesture-based utility of machines that are currently being operated manually. Different approaches and combinations of techniques can be used for classifying hand gestures using deep learning. This project aims to explore and develop a system that can recognize and classify hand gestures using deep learning methods and evaluate the extent to which the combination of CNN with LSTM and GRU (Gated Recurrent Unit) model assists in addressing this problem better. Furthermore, the effects of data augmentation on the models were explored. The results of the evaluation metrics suggested that the combination of CNN, GRU, and LSTM teamed with data augmentation, outperformed other methods in terms of both lesser computational expenses, model loss behavior, and better performance accuracy for the chosen Hand Gesture Recognition Kaggle dataset.

## Results
Evaluating multiple cutting-edge deep learning image recognition models such as CNN, CNN-LSTM and CNN-GRU, with and without augmented data provided an in-depth insight into their workings on a public dataset available on Kaggle. We observed the highest accuracy and a comparable speed for execution for the CNN-LSTM model which suits our requirement due to the availability of an enriched dataset. When dealing with a lower quality dataset, we can use the CNN-GRU for similar results with higher speed.
Even though both the models, CNN-LSTM and CNN-GRU produced similar results when it came to accuracy, partly due to the enriched nature of the dataset in which each gesture class is represented with almost 200 samples without data augmentation, CNN-LSTM can be selected for this particular use case over CNN-GRU because of its inherent nature of higher accuracy when a diverse dataset is available. However, for a dataset with lesser diversity and sample size, a CNN-GRU approach can perform better.

![image](https://user-images.githubusercontent.com/98535942/218255879-17fded5a-6ca4-41ed-9720-c0f0891e1420.png)
                                            *Fig. Confusion Matrix*

![image](https://user-images.githubusercontent.com/98535942/218255891-5d8ad1e5-e5e7-4bf6-ac69-4955ab4f9116.png)
*Fig. Accuracy Scores per epochs*

![image](https://user-images.githubusercontent.com/98535942/218255922-bd80efb3-2731-4e62-a427-cb3b352a9677.png)
*Fig. Loss per epochs*

<img width="320" alt="image" src="https://user-images.githubusercontent.com/98535942/218256004-e5e39483-20dd-4b45-85c1-9c082b223f7e.png">

# READ FOR PROJECT CODE EXECUTION AND OVERVIEW:
Steps to run “Hand gesture recognition using deep learning code (dmml2_final_code.ipynb)”:
1. Download data from the Kaggle website ( https://www.kaggle.com/datasets/gti-upm/leapgestrecog ).
2. Upload data to personal google drive to mount data to Google Colab.
3. In the “Mount data from google drive” section of code,

  a. Using this you can mount your google drive to Google Colab.
![image](https://user-images.githubusercontent.com/98535942/218255746-e4aa830a-ca27-439d-8ebf-5f7fa2d95245.png)

  b. Get the path for data using the following steps:
![image](https://user-images.githubusercontent.com/98535942/218255754-962eb611-9b92-4479-ac5e-ebe7f05ac1d4.png)

  c. Change the path of project_folder in code.
![image](https://user-images.githubusercontent.com/98535942/218255771-9d62180f-d3aa-476c-ba52-13f2f65f8345.png)

4. Run all the following cells at once or one by one to execute the final code for results.
