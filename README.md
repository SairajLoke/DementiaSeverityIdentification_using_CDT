
# DementiaSeverityIdentification_using_CDT

***Project code made for a Kaggle competition named  as AI of GOD hosted by IIT Dhanbad***

[Link to competition, my ranking for 1 submission.](https://www.kaggle.com/competitions/concetto22/leaderboard)

**Background :**
Dementia is one of the most common neurocognitive syndromes in the world, in which the memory and the ability to perform daily life activities deteriorate and get worse. If detected early, it can help in better management of the disease and can save a person from a lifelong dependency on severe medication.

**Clock Drawing Test - CDT**: The CDT is a proven preliminary test for detection of neurocognitive diseases like dementia. The patient is given a pen and a paper and he is asked to draw an analog clock on it and show the time "11:10". Based on how the patient draws, a medical practitioner can detect the chances of the patient suffering from dementia.

**The goal of the competition** : Participants have to digitalize the process of CDT by using deep learning models utilizing the dataset of hand-drawn clock images. The severity of the disease is specified in the range of 0-5 (0 indicating the worst case and 5 showing no sign of Dementia.)

Acknowledgments:
We(IIT Dhanbad) thank National Health & Aging Trends Study for providing the dataset

I thank IIT DHANBAD FOR holding a competition on such a useful application of Computer Vision.


MY attempt:

1. My Entire Code is for using 3 models ( transfer learning based )  - DenseNET , VGGNet , ResNet , (and then making a ensemble for final prediction
2. Due to Model Training time restrictions on google colab , I was only able to train DenseNET for 5 epochs ( I know its quite less, but shall update this repo when I try my other method's results as well ....not for competition)

Following was the result: 

