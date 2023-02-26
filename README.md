## Melanoma Detection Assignment


In this assignment, We **(Divya, Bipul & Ashish )** have built multiclass classification model using a custom convolutional neural network in TensorFlow.

A CNN based model which can accurately detect melanoma.

### Table of Contents: 
    General Info
    Technologies Used
    Conclusions
    
    
  **1. General Information:**

   - Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert         dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. In this assignment, We (Ashish, Bipul &           Divya) are building multiclass classification model using a custom convolutional neural network in TensorFlow.
   - The model can classify images  in malignant and benign oncologicaldiseases (Actinic keratosis,Basal cell carcinoma,Dermatofibroma,Melanoma,Nevus,Pigmented benig       keratosis,Seborrheicbkeratosis,Squamous cell carcinoma,Vascular lesion).
   - The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). 
   - All images were classified according to the ISIC classification and all subsets were divided into an equal number of images except for slightly predominant           melanomas and moles.
   
  **2. Project Pipeline:**
  
- Data Reading/Data Understanding → Defining the path for train and test the images
- Dataset Creation→ Create train & validation dataset from the train directory with a batch size of 32. Also, make sure you resize your images to 180*180.
- Dataset visualisation → Create a code to visualize one instance of all the nine classes present in the dataset
- Model Building & training : Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize   pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
-  Train the model for ~20 epochs
- Write your findings after the model fit, see if there is evidence of model overfit or underfit
- Choose an appropriate data augmentation strategy to resolve underfitting/overfitting Model Building & training on the augmented data :
- Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
- Choose an appropriate optimiser and loss function for model training
   - Train the model for ~20 epochs
   - Write your findings after the model fit, see if the earlier issue is resolved or not? **Class distribution: **
   - Examine the current class distribution in the training dataset
   - Which class has the least number of samples?
   - Which classes dominate the data in terms of the proportionate number of samples? Handling class imbalances:
   - Rectify class imbalances present in the training dataset with Augmentor library. Model Building & training on the rectified class imbalance data:
   - Create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model rescale images to normalize pixel values between (0,1).
   - Choose an appropriate optimiser and loss function for model training
   - Train the model for ~50 epochs
   - Write your findings after the model fit, see if the issues are resolved or not?
    
 **3. Conclusions:**
 
 - Image augmentation got rid of overfitting
 - Rectifying the class imbalance got rid of underfitting
    
**4. Technologies Used:**

    1.TensorFlow Version:  2.8.0
    2.NumPy Version:  1.22.4
    3.Pandas Version:  1.3.5
    4.PIL Version:  7.1.2
    5.Keras Version:  2.8.0
    

**5. Contact:**

   - Divya Tyagi : divyatyagi1007@gmail.com
   - Bipul Kumar : bipulkumar90@gmail.com
   - Ashish Kulkarni : kulkarniashisha2015@gmail.com
