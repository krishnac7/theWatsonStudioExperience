
This repository demonstrates how to use IBM Data Science Experience Models feature to predict the probability of heart stroke, given the patient data

Step 1: Login to your [DSX account](https://dataplatform.ibm.com/) and click on Get Started, choose New Project

![alt text](res/image1.png)
 
 Step 2: Name your project and give it a suitable description
 
 ![alt text](res/image2.png)
 
 Step 3: Once the newly created project opens up, click on the settings tab.scroll down to Associated services menu and click add Service
 
 ![alt text](res/image3.png)
 
 Step 4: Select Machine Learning service and add new machine learning service
 
 ![alt text](res/image4.png)
 
 Step 5: Goto Add to project and select Model
 
 ![alt text](res/image5.png)
 
  Step 6: Give it a name and select Automatic Model creation and click next
  
 ![alt text](res/image6.png)
 
   Step 7: Now click on add dataset and upload the patientdataV6.csv file

 Step 8: Select the added dataset and click next
 
 ![alt text](res/image7.png)
  Step 9: Select the HEARTFAILURE column as Label Column and ALL as Feature set and click next

  ![alt text](res/image8.png)
  
  Step 10: Once training and Evaluating the model are done, a summary of the model is provided 

  
  ![alt text](res/image9.png)
  
  Step 11: Save the model
  <br>Step 12: Open the model and navigate to Test
 <br> Step 13: Input the values you want to predict and click predict
  
  ![alt text](res/image10.png)
  
 step 14: An output bar chart shows the probability of getting a stroke
  
  ![alt text](res/image11.png)  

  