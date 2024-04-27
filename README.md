# Silvis - Virtual Gymnastic Trainer Application


## Project Objective  
Create an application that acts as a Virtual Gymnastic Trainer to facilitate older adults to train on suggested gymnastic posture which gives positive health impact. 

## Application Function & Features 
Users’ Exercise Posture Correction
Exercise Reps Counting
Program Progress and Health Metrics Tracking and and Monitoring 


## Methodologies: 

- Post-Processing on the model Google MediaPipe Pose with posture estimation algorithms
- Exercise Live Demonstration with 3D Character rigged and animated by ThreeJs Automation and Blender, Postures correctness confirmed by Certified Trainer
- User Personal Profile and Customisation server based on Python flask and RESTful API architecture 


## Estimation Model Accuracy
![image](https://github.com/chesterchan1119/Silvis---Virtual-Gymnastic-Trainer/assets/110362704/e77dbcb0-e44a-4dd6-9f8a-c56e46eabc3b)
COCO api has the evaluation metric, OKS calculated on at most 20 top-scoring detection per image, after all, person is the merely target category. With the prevalence of average precision (AP) and average recall (AR) in assessing classification tasks, the following metric illustrates the AP and AR over various IoU, ranging from 0.5 to 0.95 in a 0.05 interval increment and various objects area. 

The mean Average Precision (mAP) and mean Average Recall (mAR) over different IoU starting from 0.5, where detection is considered as correctly predicted TP, to 0.95 is 0.943 and 0.967 respectively, indicating that the model generally identify the key points location precisely by 94.3% of the time and 96.7% of all key points were able to be correctly identified. 




## Application Architecture
![Screenshot 2024-04-27 at 11 32 39 PM](https://github.com/chesterchan1119/Silvis---Virtual-Gymnastic-Trainer/assets/110362704/0cba6819-6f52-4fcb-91ce-9cb78c7848eb)



##  View Example

### User Personal Dashboard
![image](https://github.com/chesterchan1119/Silvis---Virtual-Gymnastic-Trainer/assets/110362704/5be8ccd4-04a2-40d4-92f1-7e7538a3f48a)

### Training View
![image](https://github.com/chesterchan1119/Silvis---Virtual-Gymnastic-Trainer/assets/110362704/bc13bf01-4e74-4f5b-b4a5-21a025fabbc5)





