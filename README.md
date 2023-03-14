# Alzheimers_Project
### 1. INTRODUCTION
##### Alzheimer's Disease:
Alzheimer's Disease is an irreversible, progressive brain disorder that slowly destroys memory
and thinking skills and eventually the ability to carry out the simplest tasks.
Symptoms:
Requires a Medical diagnosis
Memory Loss and confusion are the main symptoms.
People may experience:
* Cognitive Behavioural
* Mood
* Psychological
* Inability to combine muscle
* movements, jumbled speech, or loss of appetite.

It is the cause of 60-70% of cases of dementia.
Experts haven't determined a single cause of Alzheimer's disease but they identified certain risk
factors, including:
*  Age: Most people who develop Alzheimer's disease are 65 years of age or older.
* Family History: If you have an immediate family member who has developed the
condition, you're more likely to get it.
* Genetics: Certain genes have been linked to Alzheimer's disease.

### 2. LITERATURE SURVEY
##### Stages of Alzheimer’s Disease:
Stage 1. There are no symptoms at this stage but there might be an early diagnosis based on
family history.
Stage 2. The earliest symptoms appear, such as forgetfulness.
Stage 3. Mild physical and mental impairments appear, such as reduced memory and
concentration. These may only be noticeable by someone very close to the
person.
Stage 4. Alzheimer’s is often diagnosed at this stage, but it’s still considered mild. Memory
loss and the inability to perform everyday tasks is evident.
Stage 5. Moderate to severe symptoms require help from loved ones or caregivers.
Stage 6. At this stage, a person with Alzheimer’s may need help with basic tasks, such as
eating and putting on clothes.
Stage 7. This is the most severe and final stage of Alzheimer’s. There may be a loss of
speech and facial expressions.

###### Medical Diagnosis Procedures:
* MRI (Magnetic Resonance Imaging)
* CT-Scan
* PET Scan
* EEG Scan etc.
###### Deep Learning Techniques and Models:
* Artificial Neural Networks (ANN)
* Convolutional Neural Networks (CNN)
* ResNet50 Pre-trained Model (CNN Based)
* Densenet121
* Densenet169


### 3. ANALYSIS:
##### 3.1 Datasets Analysis
###### Image Dataset:
###### 4 class of MRI Segmentation Images
Images: 5121 Images
Train – Test Split: 4098 - 1023
Classes:
1. Mild Demented
2. Very Mild Demented
3. Non-Demented
4. Moderate Demented
Source: https://www.kaggle.com/datasets/tourist55/alzheimers-dataset-4-class-of-images

##### 3.2 Problem Statement
The given problem statement is about how to detect or predict a person is having Alzheimer’s
disease or not through Images and data collected through diagnosis and surveys. The images are
the MRI Segmented scans of parts of brain and categorized into 4 classes and through surveys,
the persons were asked to give information about their health conditions and other prospects.

##### 3.3 Proposed Solutions
###### Deep Learning Techniques implemented on Image Dataset:
1. Artificial Neural Networks (ANN)
Activation Functions used: ReLu, Sigmoid.
2. Convolutional Neural Networks (CNN)
Activation Functions used: ReLu, Softmax.
Optimizer: Adam Optimizer
Callbacks: Early Stopping Technique
3. ResNet50 (CNN based)
Activation Functions used: ReLu, Softmax.
Optimizer: rmsprop Optimizer
Callbacks: Early Stopping Technique
4. Densenet121 - 120 Convolutions and 4 Average Pooling Layers 
5. Densenet169 - 169 Layers 

###### From the above implementations we obtained:
*  Symptoms which lead to Dementia and eventual Alzheimer’s
*  Prediction of Alzheimer’s through Images and Numerical data.
*  Trends which are major factors of causing or factoring in developing of Alzheimer’s.
