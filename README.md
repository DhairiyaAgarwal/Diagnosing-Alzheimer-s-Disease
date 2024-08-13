# Diagnosing-Alzheimer-s-Disease


Alzheimer's-Disease-Classification-
Alzheimer's disease (AD) is a degenerative ailment illustrated by the build-up of certain proteins that cause the brain to shrink and ultimately experience cell death. The impact of AD extends far beyond the individual, affecting families, caregivers, and society as a whole, underscoring the urgent need for computer-aided detection to enhance early diagnosis and treatment. Early detection means the opportunity for proactive management, and planning, potentially slowing disease progression and enhancing quality of life. Numerous Machine Learning (ML) and Convolutional Neural Network (CNN) models have been reported in the literature to detect AD stages. While CNN models trained for AD detection offer notable advantages over classic ML algorithms like k-NN and Decision Trees, their accuracy was less due to training on small datasets. In this study, we propose employing the baseline CNN model to predict the four distinct stages of AD (NonDemented, VeryMildDemented, MildDemented, and ModerateDemented) using a curated dataset comprising 6,400 grayscale MRI images sourced from the publicly available database. Numerous CNN baseline models and six pre-trained models were trained for the identification of various stages of AD. The baseline CNN model demonstrated excellent performance, achieving an accuracy of 99.00%. Among transfer-learning-based CNN models, a streamlined pre-trained model based on Xception, demonstrated notable performance and was not better than the baseline CNN model in the early prediction of AD stages. With an enhanced ability to detect AD stages, the proposed baseline CNN model can assist healthcare professionals in making precise diagnostic assessments, guiding accurate therapeutic decisions, and tailoring care plans to individual needs, thereby improving patient outcomes.  The proposed baseline CNN model is available at the GitHub repository- “https://github.com/PGlab-NIPER/DhairiyaAgarwal-Alzheimer_Disease_Classification”.
Package requirements:
•	python = 3.9
•	tensorflow=2.11.0
•	scikit-learn
•	numpy
•	pandas
•	scipy
Repository files:
The files contained in this repository are as follows:
•	Readme file: General information
•	Prediction_model.zip: Trained model
•	Prediction_Alzheimer_Disease.py: Main script to run prediction
•	Samples: Folder where images to be classified are to be saved
Usage:
_NOTE: _ Remember to activate the corresponding conda environment before running the script, if applicable.
Input: Image file (image.jpg) for "Samples" folder
Output: result.csv
**Execution: ** 
Step 1: Install Anaconda3-5.2 or above.
Step 2: Install or upgrade libraries mentioned above (python, numpy, pandas, tensorflow, scikit-learn, scipy).
Step 3: Download code in zip format and extract all zipped files.
Step 4: Save the images to be predicted in "Samples" folder.
Step 5: Then execute the script and the result automatically saved to the “result.csv” folder.  



