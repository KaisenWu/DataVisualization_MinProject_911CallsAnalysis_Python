# DataVisualization_MinProject_911CallsAnalysis_Python

Project Overview:
This project analysis the 911 calls dataset by different ares, reasons and time.

About The Dataset
The dataset is from Kaggle, url:https://www.kaggle.com/mchirico/montcoalert

The features explainations are below:
* lat : String variable, Latitude
* lng: String variable, Longitude
* desc: String variable, Description of the Emergency Call
* zip: String variable, Zipcode
* title: String variable, Title
* timeStamp: String variable, YYYY-MM-DD HH:MM:SS
* twp: String variable, Township
* addr: String variable, Address
* e: String variable, Dummy variable (always 1)

The main process of the project:
  1. Data preperation.
  2. EDA
  3. Data visualization.
  
The main libraries which was used in this project:
  1. pandas
  2. numpy
  3. matplotlib
  4. seaborn
  
The main techniques whcih used in this project:
  1. String processing.
  2. Datetime processing.
  3. Dataframe restructuring.
  4. Time series plot.
  5. Lambda function.
  6. Dataframe index processing.
  7. Features correlation analysis and heatmap.
  8. Clustermap.
  
 The main data viz of the project:
  1. countplot of the Day of Week column with the hue based off of the Reason.
  <img width="311" alt="image" src="https://user-images.githubusercontent.com/93168873/214451344-67dd9097-8f6f-4194-a574-8bc335d64234.png">

  2. Create linear fit on the number of calls per month.
  <img width="290" alt="image" src="https://user-images.githubusercontent.com/93168873/214451429-74e5fa52-4be5-4b1b-879c-46777f94ee92.png">

  3. Time series plot which group by 'Date' when the reason is 'Trafic'. 
  <img width="337" alt="image" src="https://user-images.githubusercontent.com/93168873/214451478-2d1cf928-1397-476c-9e4e-231146fdf423.png">

  4. Heatmap.
  <img width="418" alt="image" src="https://user-images.githubusercontent.com/93168873/214451582-0778e855-fdc6-4350-9f13-0b5469056f09.png">

  5. Clustermap:
  <img width="293" alt="image" src="https://user-images.githubusercontent.com/93168873/214451703-da5d5ec1-ea8b-4fa7-87d1-27d60d3dc3dd.png">
