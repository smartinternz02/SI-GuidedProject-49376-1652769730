# SI-GuidedProject-49376-1652769730
# A Gesture-based Tool for Sterile Browsing of Radiology Images Using IBM Watson

In our project 
1. We have used CNN(Convolution Neural Network) to train the model using various images of different hand gestures.
2. Made a wweb application using flask where the user can upload the image which he wants to browse through. After the image is uploaded, the integrated webcam 
   is used to capture the video frame using OpenCV. The gesture captured in the frame is compared with the trained images and is identified.
if the prediction is,
0 - image converted to rectangle
1 - image is Resized into (200,200)
2 - image is rotated by 45॰ 
3 - image is blurred  
4 - image is Resized into (400,400) 
5 - image is converted into grayscale

3. We have also deployed the model on IBM Watson Studio

# Output
Home Page
![Home Page](https://user-images.githubusercontent.com/98869876/171177929-cb05a2d1-e9c4-4223-ac0c-bc651275ee9e.png)

Intro Page
![Intro](https://user-images.githubusercontent.com/98869876/171177971-a4e86c18-dffe-4ee9-9f1d-b6628ae72b7e.png)

Launch Page
![launch](https://user-images.githubusercontent.com/98869876/171178001-dd60dbac-cc94-4b7e-bf91-924ae4067043.png)

Result for hand gesture 4
![output1](https://user-images.githubusercontent.com/98869876/171178106-99c01ad2-c9b5-4fc9-89b3-93d6e5e8dc7d.png)

Result for hand gesture 5
![output2](https://user-images.githubusercontent.com/98869876/171178124-ac10adff-8d70-46ff-b6d4-45f4ba041414.png)

# Dataset 
https://drive.google.com/drive/folders/1mbkYtG2zzFr5ATJxr_B8Hdtm3rl6PCg8?usp=sharing

# Model Training and Testing
https://drive.google.com/drive/folders/1TUyrB4_J86K6BdF2vcrNAU7841qNNlD-?usp=sharing

# Flask
https://drive.google.com/drive/folders/12vNQprligvbnAB7GGlo7AOE274QAmGbW?usp=sharing

# IBM Deployment Files
https://drive.google.com/drive/folders/1-E7t9mnjsqql73AxtfS9nyLNduIHKGeP?usp=sharing

# Video Demonstration link
https://drive.google.com/file/d/1n6FgfhbHV0jpTG-GLAHT0F3QlMoaUICX/view?usp=sharing


   
