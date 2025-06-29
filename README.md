🔐 Face Recognition System using AWS Cloud Services
This project is a cloud-native, AI-powered facial recognition system designed using various AWS services to provide real-time identity verification, emotion detection, and facial attribute analysis. It leverages the power of Amazon Rekognition and AWS Lambda to deliver a highly scalable, secure, and efficient facial analysis solution.

![Screenshot 2025-03-28 220356](https://github.com/user-attachments/assets/65a85461-11a8-4fa5-89e7-638cb4f53209)



🚀 Project Overview
We have developed a Facial Attribute Recognition System that:

Detects faces in uploaded images.

Analyzes various facial features like emotion, gender, age, eye/mouth state, beard presence, and eyewear.

Uses cloud infrastructure for scalability, real-time performance, and cost-effectiveness.

🧠 Key AWS Services Used
Amazon Rekognition: AI service for detecting and analyzing facial features.

Amazon S3: Cloud storage for images and associated metadata.

AWS Lambda: Serverless compute to handle backend tasks without managing servers.

AWS IAM: Manages secure access control and authentication for AWS resources.

🎯 Objectives
✅ Build a robust facial recognition system using AWS services.

✅ Enable real-time face detection, attribute analysis, and emotion recognition.

✅ Ensure data security and privacy using AWS IAM and S3 encryption.

✅ Optimize performance and reduce cost using serverless architecture.



Use python 3.7.9

# steps to run code

1 Create aws account if not created yet.
  Link - for creation - https://aws.amazon.com/
  
2 Create a **user** using IAM management Console in aws account with one Policy named as **AmazonRekognitionFullAccess**
  After creating user it will provide a csv file which contains credentials . 
  
  csv file name - new_user_credentials.csv
  
3 Download csv file and copy that file to Facial-Analysis-using-Amazon-Rekognition Directory

4 Install all library mentioned in requiremets.txt

5 then run app.py file.


