# Project Overview
This project was completed as part of the Dataslayer 2.0 Competition held by Telkom University, Bandung, Indonesia. We were tasked to build a model that detects if someone is falling in a given image. It is a Kaggle competition where teams compete to get the highest accuracy as possible. 

# The Dataset
The given dataset has two main folders: train and test. The test dataset is used by the model in the end. The train dataset consists of images in subfolders (structure provided in 'File Structure.pdf'), which represents in which category an image belongs to (fall or non_fall) and in which subcategory it belongs to. There are 6 subcategories for each fall and non_fall categories. It is imporatant to note that there were 4 subjects (person) in the dataset. Each subject has their own images of fall and non_fall. 

6 subcategories of fall: 
1. Backward falls
2. Forward falls
3. Left falls
4. Right falls
5. Sitting falls
6. Standing falls

6 subcategories of non_fall: 
1. Jumping
2. Laying
3. Picking
4. Squat
5. Stretching
6. Walking

# The Team
Our team SlemanFaiz consists of 3 people: 
1. Tristan Khayru Abiyudha, as Team Leader
2. Salman Faiz Hidayat, as Member
3. Adam Maulana Haq, as Member

# Result
There were 3 main algorithms we experimented with: 
1. InceptionV3
2. ResNet50
3. Pose Detection 

The one that yielded the most accuracy was the InceptionV3 model, with an accuracy of 97% (dataslayer-slemanfaiz.ipynb). Thus, we ranked 12th overall out of 200+ teams. The ResNet50 yielded an accuracy of 91.8% (ResNet50.ipynb), and the pose detection with 88% (pose-detection.ipynb). 

# Running Our Notebooks
The notebook can be run in any environment you would like. Make sure to adjust the directory of your dataset and install all the necessary dependencies. 
