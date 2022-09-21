# Brain-Tumour-Segmentation

## Inspiration
One of my junior had been suffering from brain tumour. He was in 9th grade when i was in 11th grade. His operation was very critical and the doctor could not save him. This was my first instance where i deep dived into brain tumour but at that time i did not how brain tumours are segmented. But , in my last summer training i got to know about this more.

A brain tumor is a mass or growth of abnormal cells in the brain. In India, every year **40.000- 50,000** patients are diagnosed with a brain tumor. Of these **20** percent are children.

More than **500** new cases are diagnosed with brain tumour everyday worldwide. Number of patients with tumours that cause brain metastases is even higher than that. This is the most common type of cancer among children. The incidence and prevalence of brain tumour is growing in India.

Brain tumour is a deadly disease. However, it can be treated by various methods but majority of patients die within **9-12** months and less than **3%** survive more than 3 years.

## What it does
**Brain tumor detection at early stages can increase the chances of the patient's recovery after treatment.**
So, in this project we will take datasets from Kaggle and perform brain tumour segmentation using UNET.

Segmentation helps to identify where objects of different classes are present in an image. UNet is a convolutional neural network architecture that expanded with few changes in the CNN architecture.

UNET is used to separate the different tumor tissues (active tumor, edema and necrosis) from normal brain tissues: GM, WM, and CSF.  It  also includes the performance and quantitative analysis of this image.

## How we built it
It is done by using deep learning concepts of UNET , Keras , K-means clustering algorithm , and machine learning .

We have taken the datasets of images from Kaggle and applied ML and DL using python.
Then:-
*Data is splitted into training and validation split in 90:10 ratio.
*Function to calculate the DSC score.
*Model is prepared.
*Model is fitted.
*Training and testing is done on the model.
*Graph is plotted using Matplotlib.

## Challenges we ran int0
We had to deal with large number of images as datasets. 
Running 20 epochs took too much time.


## Accomplishments that we're proud of
This project made me learn so much new things and my resume got a big boost after this project.

## What we learned
First of all this project is coded in python and it has used various python libraries like numpy ,pandas and matplotlib. So , learnt all these.
Then got to learn various machine learning and deep learning algorithms.
 

## What's next for Brain Tumour Segmentation
I want to take this project further and work on more datasets.
