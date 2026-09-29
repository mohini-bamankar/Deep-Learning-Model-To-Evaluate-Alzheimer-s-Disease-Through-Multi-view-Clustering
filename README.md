🧠 Automated Alzheimer’s Disease Detection using Deep Learning & Multi-View Clustering

An automated end-to-end framework designed to assist in early-stage Alzheimer’s Disease detection using brain MRI scans. This system processes multi-view brain images (Axial and Sagittal) from the ADNI dataset and categorizes them into 6 distinct clinical stages of cognitive progression.   


📌 Project Overview : 
Early diagnosis of Alzheimer's Disease is critical for patient care, but analyzing complex medical scans manually is time-consuming. This project combines Deep Learning (Channel Boost CNN) with Inverse Matrix Factorization and a Decision Tree Classifier to classify brain scans accurately and reliably.   

🎯 Key Features : 
Multi-View Analysis: Evaluates both Axial and Sagittal perspectives for a comprehensive view.  
Automated Data Pipeline: Converts DICOM (.dcm) scans to standardized JPEG images with absolute grayscaling.   
Dual Optimization System: Uses a Channel Boost CNN (CB-CNN) alongside matrix factorization for feature extraction.  
6-Stage Classification: Groups brain scans into 6 clinical categories:
      CN: Cognitively Normal   
      SMC: Subjective Memory Complaint   
      EMCI: Early Mild Cognitive Impairment   
      MCI: Mild Cognitive Impairment   
      LMCI: Late Mild Cognitive Impairment   
      AD: Alzheimer's Disease   
      
🛠️ Tech Stack & Dependencies 
Language: Python   
Deep Learning: TensorFlow, Keras  
Computer Vision: OpenCV   
Data Processing: NumPy, Pandas   
Machine Learning: Decision Trees (scikit-learn) 

📈 Results
Cluster Error Rate: Achieved a low Root Mean Square Error (RMSE) of 2.32, indicating high stability and accuracy across multi-view clusters.
