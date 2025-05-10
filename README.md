# AlzheimerConv
## 🌄 Background
Alzheimer’s disease is a brain disorder that slowly takes away a person’s memory, thinking skills, and ability to carry out simple tasks. It usually affects older adults, starting with forgetfulness and confusion, and over time, it can make people unable to recognize loved ones or take care of themselves.

Here I present a very simple,primitive and shallow convolutional network for detecting Alzheimer's Patients, from their Brain MRI Scans.

### 📚 Dataset
For this particular purpose, I have used this <a href=https://www.kaggle.com/datasets/uraninjo/augmented-alzheimer-mri-dataset/data>Dataset</a> \
The data consists of MRI images. The data has four classes of images both in training as well as a testing set:
<ol>
  <li>Mild Demented</li>
  <li>Moderate Demented</li>
  <li>Non Demented</li>
  <li>Very Mild Demented</li>
</ol>

⭐ The dataset has pre-saved augmented images to enhance the variability of the training data for the Convolutional Model.

<p align='center'><img src="https://github.com/user-attachments/assets/1070289b-a9f6-4342-a6c7-db52a77aa64d" alt="disp" width="500"></p>
<p align='center'><img src="https://github.com/user-attachments/assets/c40f7b5a-b8f2-426f-a3ff-55748d333ab1" alt="disp" width="500"></p>




### 🏗️ Model Architecture
![image](https://github.com/user-attachments/assets/42e523a1-58d0-4c11-9583-a09e7cb4694a)

### 📊 Model Classification Report

<p align='center'><img src="https://github.com/user-attachments/assets/3679891d-1dd7-4ff6-bdf6-310b735415c6" alt="disp" width="500"></p>
<p align='center'>Reported an overall accuracy of 82% </p>

### ↗️ Future Direction
By virtue of Transfer-Learning, use a pre-trained deep convolutional neural network using the same dataset, to compare the performance and most importantly look out for the performance v/s computation cost tradeoff 💪.













