# Identification-of-Autism-in-Children-using-Static-Facial-Features-and-Deep-Neural-Networks

## Autism Detection using Resnet50 & Xception Transfer Learning
In this project we are using Resnet50 and Xception algorithm with transfer learning technique to train Autism detection model. To train both algorithms we have used same dataset given by you. This dataset consists of two different classes such as ‘Autistic’ and ‘Non-Autistic’ and below screen showing images from dataset folder
![image](https://github.com/user-attachments/assets/96c1e0b1-4d07-43aa-af01-288f88bd5e09)


So by using above images we will train both algorithms.
To implement this project we have designed following modules
1)	Upload Autism Dataset: using this module we will upload dataset images to application
2)	Preprocess Dataset: using this module we will read each images and then resize all images to equal sizes and then normalize pixel values. Split dataset into train and test where application used 80% images for training and 20% for testing
3)	Run Resnet50 Algorithm: processed train images will be input to Resnet50 transfer learning algorithm to train Autism prediction model. This model will be applied on test images to calculate prediction accuracy
4)	Run Xception Algorithm: processed train images will be input to Xception transfer learning algorithm to train Autism prediction model. This model will be applied on test images to calculate prediction accuracy
5)	Comparison Graph: using this module we will plot comparison graph between both algorithms
6)	Predict Autism from Test Image: using this module we will upload test image and then algorithm will predict weather image is ‘Autistic’ or ‘Non- Autistic’.
## SCREENSHOTS
To run project double click on ‘run.bat’ file to get below screen
![image](https://github.com/user-attachments/assets/fc59180a-540d-44c9-9351-64437aad67f2)


In above screen click on ‘Upload Autism Dataset’ button to upload dataset and get below output
![image](https://github.com/user-attachments/assets/892d2301-e4f3-49e9-90a7-38c7c1ddbb63)


In above screen selecting and uploading ‘Autism Dataset’ folder and then click on ‘Select Folder’ button to load dataset and get below output
![image](https://github.com/user-attachments/assets/9c4473ad-b126-4505-a23b-f5b7f34231c1)


In above screen dataset loaded and now click on ‘Preprocess Dataset’ button to read and process all images and get below output
![image](https://github.com/user-attachments/assets/2b1f9aaa-8454-414f-affc-75c96df34578)


In above screen dataset processed and to check weather images processed properly I am showing sample image and now close above image and we can see dataset contains 412 images where application using 329 images for training and 83 for testing. Now click on ‘Run Resnet50 Algorithm’ button to train Resnet50 and get below output
![image](https://github.com/user-attachments/assets/6dc47fb6-fd10-4c53-8953-4e35acf28397)


In above screen Resnet50 training completed and we got accuracy as 96% and in confusion matrix graph x-axis represents PREDICTED classes and y-axis represents TRUE CLASSES. In above graph same colour boxes represents INCORRECT prediction count and different colour boxes represents CORRECT prediction count and Resnet50 predict only 3 records as incorrectly. Now close above graph and the click on ‘Run Xception Algorithm’ button to train Xception and get below output
![image](https://github.com/user-attachments/assets/59c3762f-32db-4b24-9011-ad1eb3ea410b)


In above screen Xception training completed and with Xception we got 84% accuracy and in confusion matrix graph we can see Xception predict 13 records incorrectly. So from both algorithms Resnet50 got high accuracy. Now click on ‘Comparison Graph’ button to get below graph
![image](https://github.com/user-attachments/assets/9b98f1ef-2c07-4616-92c5-0500b65e07e4)


In above graph x-axis represents algorithm names and y-axis represents accuracy, precision, recall and F1SCORE in different colour bars. In above graph we can see Resnet50 got high performance. Now close above graph and then click on ‘Predict Autism from Test Image’ button to upload test image and get below output
![image](https://github.com/user-attachments/assets/02f55290-ffd9-4986-bc30-a439c75c7e67)


In above screen selecting and uploading ‘11.jpg’ and then click on ‘Open’ button to get below prediction output
![image](https://github.com/user-attachments/assets/575c18ef-261c-49af-bd08-de70ee77837e)


In above screen image is classified as ‘Autistic Detected’ and now upload other image and get output
![image](https://github.com/user-attachments/assets/6e762114-829d-4c87-9354-643845d0bd5f)


In above screen selecting and uploading ‘1.jpg’ and then click on ‘Open’ button to upload image and get below output
![image](https://github.com/user-attachments/assets/e0ec5f53-7d53-41c8-83eb-f0a0429811c9)


In above screen image is classified as ‘Non Autistic’. Similarly you can upload and test other images

