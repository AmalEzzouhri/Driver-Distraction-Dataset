# Driver-Distraction-Dataset



Researchers often build their own datasets purely for their studies, many of which are never published. The dataset of StateFarm on [Kaggle](https://www.kaggle.com/c/state-farm-distracted-driver-detection) was the first publicly available dataset used for competition purposes only. They defined ten distractions to be detected: safe driving, texting using right hand, talking on the phone using right hand, texting using left hand, talking on the phone using left hand, operating the radio, drinking, reaching behind, doing hair and makeup, and talking to a passenger. In \cite{AUC2018}, the authors created a new Distracted Driver dataset similar to the StateFarm's dataset (i.e., it is composed of the same ten distraction activities). A total of 44 volunteers from seven different countries participated in the creation of this dataset. However, the dataset is not balanced and not well annotated, as shown in fig. \ref{AUC_dataset}. Moreover, some drivers did not participate in the ten different activities. ![dataset](https://user-images.githubusercontent.com/36284282/131345876-b89ad3b3-67c9-4294-82ca-0c4e1c320492.png) 


We referred to the aforementioned datasets to compile our own dataset using an efficient data collection strategy; it required less time than correcting the existing datasets. 
Ten driver distraction classes were defined including:
   \begin{itemize}
    \item C0: Safe driving
    \item C1: Texting - right hand
    \item C2: Talking on the phone - right hand
    \item C3: Texting - left hand
    \item C4: Talking on the phone - left hand
    \item C5: Operating the radio
    \item C6: Drinking
    \item C7: Reaching behind
    \item C8: Tidying up hair or applying makeup
    \item C9: Talking to passenger
  \end{itemize}

