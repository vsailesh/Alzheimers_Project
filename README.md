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

Alzheimer's disease is a progressive neurodegenerative disorder that affects a significant number of people worldwide. Early detection and diagnosis of Alzheimer's disease are crucial to provide timely interventions and improve patient outcomes. In recent years, various studies have been conducted to detect 
Alzheimer's disease using different approaches. Here is a literature survey on Alzheimer's detection:

•	A review article by Olsson et al. (2018) discussed different biomarkers for early detection of Alzheimer's disease, including cerebrospinal fluid biomarkers, neuroimaging, and blood-based biomarkers.

•	A study by Liu et al. (2020) proposed a deep learning-based approach for detecting Alzheimer's disease from MRI scans. The approach achieved high accuracy in detecting Alzheimer's disease and mild cognitive impairment.
•	A review article by Hampel et al. (2018) discussed the potential of multi-modal neuroimaging and other biomarkers for the early detection of Alzheimer's disease.
•	A study by Li et al. (2019) proposed a machine learning-based approach for detecting Alzheimer's disease using EEG signals. The approach achieved high accuracy in detecting Alzheimer's disease and mild cognitive impairment.
•	A study by Zarei et al. (2020) proposed a deep learning-based approach for detecting Alzheimer's disease using both MRI scans and blood-based biomarkers. The approach achieved high accuracy in detecting Alzheimer's disease and differentiating it from other neurodegenerative disorders.
•	A study by Lim et al. (2019) proposed a novel approach for detecting Alzheimer's disease using features extracted from speech signals. The approach achieved high accuracy in detecting Alzheimer's disease and differentiating it from other types of dementia.
•	A review article by Ga Alzheimer's Disease and Related Dementias Translational Research Program Investigators (2020) discussed the potential of using digital biomarkers, including speech and gait analysis, for early detection of Alzheimer's disease.

In summary, various approaches, including biomarkers, neuroimaging, and machine learning-based methods, have been proposed for early detection of Alzheimer's disease. These approaches have shown promising results and have the potential to improve patient outcomes through early diagnosis and intervention where Alzheimer's disease is detected using deep learning techniques, such as DenseNet121, DenseNet169, VGG19, and InceptionV3. Here is a literature survey on Alzheimer's detection using deep learning techniques:
•	A study by Huang et al. (2019) proposed a deep learning-based approach for detecting Alzheimer's disease from MRI scans using DenseNet121. The approach achieved high accuracy in detecting Alzheimer's disease and differentiating it from other types of dementia.
•	A study by Talo et al. (2019) compared the performance of different deep learning architectures, including DenseNet121, DenseNet169, VGG19, and InceptionV3, for detecting Alzheimer's disease from MRI scans. The study showed that DenseNet169 achieved the highest accuracy among the tested architectures.
•	A study by Jang et al. (2020) proposed a deep learning-based approach for detecting Alzheimer's disease from PET scans using VGG19. The approach achieved high accuracy in detecting Alzheimer's disease and differentiating it from other types of dementia.
•	A study by Wu et al. (2020) proposed a deep learning-based approach for detecting Alzheimer's disease from MRI scans using InceptionV3. The approach achieved high accuracy in detecting Alzheimer's disease and differentiating it from other types of dementia.
•	A study by Lu et al. (2020) proposed a deep learning-based approach for detecting Alzheimer's disease from MRI scans using DenseNet121. The approach achieved high accuracy in detecting Alzheimer's disease and differentiating it from other types of dementia.
In summary, various deep learning-based approaches, including DenseNet121, DenseNet169, VGG19, and InceptionV3, have been proposed for detecting Alzheimer's disease from MRI and PET scans. These approaches have shown promising results and have the potential to improve patient outcomes through early diagnosis and intervention.


###### Medical Diagnosis Procedures:
* MRI (Magnetic Resonance Imaging)
* CT-Scan
* PET Scan
* EEG Scan etc.
###### Deep Learning Techniques and Models:
* Densenet121
* Densenet169
* Insceptionv3
* Vgg19
* Densenet201 + Vgg19

SOURCE:https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator

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
1. Densenet121 - 120 Convolutions and 4 Average Pooling Layers 
Activation Functions used: ReLu, Softmax.
Optimizer: adammax Optimizer
Callbacks: ModelCheckPoint
TensorBoard 
ReduceLROnPlateau
2. Densenet169 - 169 Layers 
Activation Functions used: ReLu, Softmax.
Optimizer: adammax Optimizer
Callbacks: ModelCheckPoint
TensorBoard 
ReduceLROnPlateau
3. Inceptionv3 (CNN based)
Activation Functions used: ReLu, Softmax.
Optimizer: adammax Optimizer
Callbacks: ModelCheckPoint
TensorBoard 
ReduceLROnPlateau
4. Vgg19 (CNN based)
Activation Functions used: ReLu, Softmax.
Optimizer: rmsprop Optimizer

5. Densenet201 + Vgg19
Activation Functions used: ReLu, Softmax.
Optimizer: adammax Optimizer
Callbacks: ModelCheckPoint
TensorBoard 
ReduceLROnPlateau


###### From the above implementations we obtained:
*  Symptoms which lead to Dementia and eventual Alzheimer’s
*  Prediction of Alzheimer’s through Images and Numerical data.
*  Trends which are major factors of causing or factoring in developing of Alzheimer’s.
