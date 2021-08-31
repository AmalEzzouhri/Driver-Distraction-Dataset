# Driver-Distraction-Dataset



Researchers often build their own datasets purely for their studies, many of which are never published. The dataset of StateFarm on [Kaggle](https://www.kaggle.com/c/state-farm-distracted-driver-detection) was the first publicly available dataset used for competition purposes only. They defined ten distractions to be detected: safe driving, texting using right hand, talking on the phone using right hand, texting using left hand, talking on the phone using left hand, operating the radio, drinking, reaching behind, doing hair and makeup, and talking to a passenger. In 2018, a new [Distracted Driver dataset](https://abouelnaga.io/projects/auc-distracted-driver-dataset/) similar to the StateFarm's dataset was created (i.e., it is composed of the same ten distraction activities). A total of 44 volunteers from seven different countries participated in the creation of this dataset. However, the dataset is not balanced and not well annotated. Moreover, some drivers did not participate in the ten different activities. 

![dataset](https://user-images.githubusercontent.com/36284282/131345876-b89ad3b3-67c9-4294-82ca-0c4e1c320492.png) 


We referred to the aforementioned datasets to compile our own dataset using an efficient data collection strategy; it required less time than correcting the existing datasets. 
Ten driver distraction classes were defined including:
   C0: Safe driving,
   C1: Texting - right hand,
   C2: Talking on the phone - right hand,
   C3: Texting - left hand,
   C4: Talking on the phone - left hand,
   C5: Operating the radio,
   C6: Drinking,
   C7: Reaching behind,
   C8: Tidying up hair or applying makeup,
   C9: Talking to passenger.
   
   
# Data Collection setup
   
To study the driver's behavior in real traffic situations, we conducted experiments using an instrumented vehicle, which comprises:

(i) a camera, installed above the vehicle's side window and oriented toward the driver, and
(ii) a Mobile Digital Video Recorder (MDVR).

One part of the data was collected in real-world driving conditions. The other part was collected by asking drivers to simulate different types of driving behaviors in the instrumented vehicle, but without moving the vehicle for safety reasons. Nine drivers were involved in the experiment. Each of them was asked to perform the ten activities separately (i.e., one activity for each video sequence) while driving or pretending to drive, which took about 15 minutes for each driver resulting in about 450 images per class per driver. After the manual examination, a total of about 38 thousand images were preserved. Figure bellow illustrates the data distribution over the classes.

 
![data_distribution](https://user-images.githubusercontent.com/36284282/131348814-637ddb69-2e56-4df2-988b-cf1629daac06.png)

# Privacy
This dataset is made available for academic use only. The drivers who participated in the creation of the database were invited to accept the publication of its images, and they accepted. 
# Terms & Conditions
All publications that report on research that uses the dataset should cite our publications.


# Acknowledgement
This work is partly funded by the National Agency for Road Safety (NARSA) of the Moroccan Ministry of Equipment, Transport, Logistics and Water, via the National Center for Scientific and Technical Research (CNRST).

## Download

[![CI](https://user-images.githubusercontent.com/36284282/131467359-60478c49-bd9f-4a09-9f01-5014ae7a5c39.png){height="50%" width="50%"}](https://uirabat-my.sharepoint.com/personal/amal_ezzouhri_uir_ac_ma/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Famal%5Fezzouhri%5Fuir%5Fac%5Fma%2FDocuments)


