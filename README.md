# Create a Watson Studio project and set up required services. 

## Introduction:

[<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/DSX.png" height="150"/>](http://datascience.ibm.com/) [<img src="https://raw.githubusercontent.com/Davin-IBM/Proof-of-Technology/master/DSX/images/jupyter.png" height="150"/>](http://jupyter.org/index.html)

You will use IBM's Watson Studio to perform the labs in this repository. The instructions to set up the environment are documented below. 

## Instructions:

### Step 1.  Log into your [Watson Studio](http://datascience.ibm.com/) account, then select `View All Projects`.

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Select%20View%20All%20Projects.png"/>

### Step 2.  If you have an existing project by following the signup instructions then select it, and skip to Step x.  Otherwise, click on `New Project`. 
> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Select%20New%20Project.png"/>

### Step 3. Enter the project name (eg. Watson Studio Labs), optionally a description, and then click on `Add` in the Storage section. Note if you have already provisioned cloud object storage, then just click on the `Create` button. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/New%20Project%20Panel%20-%20Add%20Storage.png"/>

### Step 4. Click on the Lite plan, and then click on `Create`. 

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Create%20Object%20Storage.png"/>

### Step 5. Optionally change the storage name, and then click on `Confirm`

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Confirm%20Creation.png"/>

### Step 6. Click on `Refresh`, and then click on `Create`

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/Click%20Refresh.png"/>

> <img src="https://github.com/bleonardb3/ThinkGov/blob/master/Images/New%20Project%20Panel%20-%20Add%20Storage.png"/>

The labs in this Proof of Technology will require the following services to be created and associated with your project. 
1. Object Storage
1. Watson Machine Learning
1. Apache Spark  

The Object Storage service instance should already exist, having been created when the Watson Studio Labs (or whatever you named it) project was created. Both the Watson Machine Learning service, and the Apache Spark service need to be created and then associated with the project.  

### Step 3.  Click on the project `Settings` tab.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Settings.png"/>

### Step 4. Scroll down to `Associated Services`, then select `Add service` and select `Machine Learning`.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Add%20Machine%20Learning%20Service.png"/>

### Step 5. Select `New`.

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20New%20Service.png"/>

### Step 6. Select the `Lite` plan. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Select%20Lite%20ML.png"/>

### Step 7. Scroll down and click `Create` and then click `Confirm`. Note, you can change the name of the machine learning service or accept the default. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Scroll%20down%20hit%20Create%20and%20then%20Confirm.png"/>

### Step 8. The Machine Learning service that you created should now appear in `Associated Services`. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/See%20ML%20in%20Associated%20Services..png"/>

### Step 9. Follow the same process as in steps 4-8, except this time add a Spark service. 


### Step 10.  We are now going to create a new notebook in our project. This notebook will be created from a url that points to the Lab-1 notebook in the github repository. Click the `Add to project` link and then the `Notebook` link as shown below. 

> <img src="https://github.com/bleonardb3/ML-POT/blob/master/Lab-1/images/Add%20Notebook.png"/>

### Step 11.  Create the notebook.

> <img src="https://github.com/bleonardb3/SparkPOT/blob/master/Lab-1/images/New%20Notebook.png"/>

1. Click the `From URL` tab under `Create Notebook`.
1. Give the notebook a name in the `Name` field, for example `Spark Lab-1` and optionally you can give it a description.
1. In the Notebook URL field, use `https://github.com/bleonardb3/SparkPOT/blob/master/Lab-1/Lab1Student-DataFrame.ipynb`.
1. Ensure that there is a `Spark Service` selected, then click the `Create Notebook` button on the bottom right of the screen.

### Step 12.  Follow the instructions in the notebook.

> <img src="https://github.com/jpatter/SparkPOT/blob/master/Lab-1/images/SparkPOT-Lab1.PNG"/>
