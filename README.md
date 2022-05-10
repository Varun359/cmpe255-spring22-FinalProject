# US Accidents Severity Prediction	

## Dataset - https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents

### Introduction 
Road accidents can be caused by a variety of meteorological and topographical factors, in addition to human mistake. Due to slick roadways, a 100-car pileup occurred recently. Road accidents are more likely under certain circumstances. Several research have been undertaken in order to acquire sufficient data on elements that may contribute to the likelihood of accidents. Nonetheless, "What are the major elements that cause road accidents?" and "How can we forecast them?" remain open questions. We propose analyzing a road accident data set collected in the United States from February 2016 to December 2021 in order to learn about the primary elements that cause accidents and maybe forecast them with a good accuracy.

### Tools / Technologies:
Programming language: Python

Libraries used: NumPy, SciPy, Pandas, Scikit-Learn.

Tools: Jupyter Notebook, Google Colab 

### Preprocessing 
The dataset includes 47 columns with severity as the output variable. This includes accidents data from 49 states. We have analysed the data and noticed that it has null values. We are planning to drop the null value columns or apply ffill or bfill methods and choose the best out of two. In preprocessing we have visualized accident data from all states. And also visualized top 10 accident states in US and top 10 accident cities in Us Analyzing accidents per year and per month. We have analysed severity by day of the week, accidents count by day and accidents count by day of the week. We have plotted Accidents and severity per hour of the day. When we have visualised the output varible, one of the output label ie., severity 2 is doiminating over all the output labels. We have also plotted the sevrity labels by years. We have plotted distribution of temperature, humidity and pressure with severity. We have plotted the hotspots of the accidents severity on the US map. We have label encoded the columns which are categorical. We have normalised the columns of the dataset using Standard scalar. And we have taken a split of 0.75 training samples and 0.25 testing samples. We have developed four machine learning models, They are:
1. Logistic Regression
2. Decision Tree
3. Convolutional Neural Network 
4. Random Forest

