# US Accidents Severity Prediction	

## Dataset - https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

### Introduction:
Road accidents can be caused by a variety of meteorological and topographical factors, in addition to human mistake. Due to slick roadways, a 100-car pileup occurred recently. Road accidents are more likely under certain circumstances. Several research have been undertaken in order to acquire sufficient data on elements that may contribute to the likelihood of accidents. Nonetheless, "What are the major elements that cause road accidents?" and "How can we forecast them?" remain open questions. We propose analyzing a road accident data set collected in the United States from February 2016 to December 2021 in order to learn about the primary elements that cause accidents and maybe forecast them with a good accuracy.

### Tools / Technologies:
Programming language: Python

Libraries used: NumPy, SciPy, Pandas, Scikit-Learn.

Tools: Jupyter Notebook, Google Colab 

Framework : Flask

### Preprocessing:
The dataset includes 47 columns with severity as the output variable. This includes accidents data from 49 states. We have analysed the data and noticed that it has null values. We are have dropped the columns with. In preprocessing we have visualized accident data from all states. And also visualized top 10 accident states in US and top 10 accident cities in Us Analyzing accidents per year and per month. We have analysed severity by day of the week, accidents count by day and accidents count by day of the week. We have plotted Accidents and severity per hour of the day. When we have visualised the output varible, one of the output label ie., severity 2 is doiminating over all the output labels. We have also plotted the sevrity labels by years. We have plotted distribution of temperature, humidity and pressure with severity. We have plotted the hotspots of the accidents severity on the US map. We have label encoded the columns which are categorical. We have normalised the columns of the dataset using Standard scalar. And we have taken a split of 0.75 training samples and 0.25 testing samples. We have developed four machine learning models, They are:
1. Logistic Regression
2. Decision Tree
3. Convolutional Neural Network 
4. Random Forest

## Preprocessing outputs:

![image](https://user-images.githubusercontent.com/55958864/167739142-9a8eec86-e4bd-4ab1-81ed-2b568c8f6289.png)

![image](https://user-images.githubusercontent.com/55958864/167739178-3a0b5d24-0758-459b-8230-a7e27e400022.png)

![image](https://user-images.githubusercontent.com/55958864/167739241-a01c9c5e-b9f2-4e3b-a99c-738a35fcb9cf.png)

![image](https://user-images.githubusercontent.com/55958864/167739262-4bb2e469-4b6a-4fe9-a659-c457f369611e.png)

![image](https://user-images.githubusercontent.com/55958864/167739314-af578109-f006-4e36-a679-7f7ca42495d5.png)

![image](https://user-images.githubusercontent.com/55958864/167739330-aa458baa-69ce-4bcb-a70d-18a44859dd89.png)

![image](https://user-images.githubusercontent.com/55958864/167739360-c253f6bd-4510-4e6e-9c84-d486f18bd0df.png)

![image](https://user-images.githubusercontent.com/55958864/167739383-9e8718e3-520e-4734-890d-55be5dc697c5.png)

![image](https://user-images.githubusercontent.com/55958864/167739401-e330c813-a693-416c-adf6-24294b93c6c8.png)

![image](https://user-images.githubusercontent.com/55958864/167739408-ba25964a-cc00-42d7-a9f4-dceec22543d8.png)

![image](https://user-images.githubusercontent.com/55958864/167739417-40b531c8-ae71-40f8-9ebf-a8b4cbbb0dbf.png)

![image](https://user-images.githubusercontent.com/55958864/167739434-d2ac7b8a-c84c-40f5-985f-fcc2ceb5ef98.png)





