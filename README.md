# 911-Call-Data-Analysis
*An analysis of 911 call data of Montgomery County in Commonwealth of Pennsylvania applying theories from* **Think like a Data Scientist: Tackle the data science process step-by-step** *book by Brian Godsey*.

**Dataset studied** : **https://www.kaggle.com/mchirico/montcoalert/version/50#**

**Description & Structure of the Data:**

The data is in csv format and the size of the file is 74.87 MB. The dataset has a total of 10 columns, and 423909 entries. In order to get a very vivid idea of the dataset, after downloading, I created a new Jupyter notebook and used Python commands to get the structure of the data. 
The following are the 10 columns of the dataset: 

●	**lat**: Latitude value of the caller - data type: Float64

●	**lng**: Longitude value of the caller - data type: Float64

●	**desc**: Description of emergency - data type: object

●	 **zip**: Zip code of the caller - data type:  Float64

●	**title**: Title of emergency - data type: object

●	**timeStamp**: Date and time of the call - data type: datetime64

●	**twp**: Town of the caller - data type: object

●	**addr**: Address of the caller - data type: object

●	**e**: Dummy variable which is always 1 - data type: int64

●	**year**: year of call - data type: int64 

**Notes on Exploration of the Dataset:**

According to ‘Think like a Data Scientist’, “Uncertainty is one of the principle characteristics of data science work. If there were no uncertainty, there would be no exploration and there would be no problem solving” (Godsey,1998, p.7). Here, the availability of dataset of the 911 calls concurs with the first step of data science process - preparing the data. Now that the data is obtained, it is time to explore and assess the data and to see whether the data is relevant and sufficient. In order to understand this, I applied my findings from Godsey’s book: understand how the data can be used to answer my questions/ attain my goals of this project. My initial goal is to understand the volume of calls in a year, specifically 2018 and also assess the nature of calls in specific regions. This would help to analyze whether the responders are equipped well enough to deal with the emergencies. For instance, if there have been more calls from a particular zip code for vehicle accidents, it means the area should be well equipped with ambulance services. In order to answer these questions, I first decided to do some descriptive statistics of the available data. 

**What I learned about this dataset:**

In this mini-project I worked with the 911 call dataset of Montgomery County, and was able to understand the various reasons for which an emergency call is made. It was interesting to understand the volume of calls made in each day, which gave a rough idea of the number of accidents happening in the County. The total number of calls made from the year of 2015 to 2018 is 423909 and in the year of 2018 alone, the number of calls made were 133290. From whatever I studied from this dataset, it can be concluded that Vehicle accidents are the major cause of 911 calls for most of the time. It should be analyzed whether these higher amount of road accidents are due to bad road conditions or traffic regulation failures. A huge relief is that Active shooter has the least number of calls recorded. There has been only 1 call made about an active shooter in the year of 2018. Also, there has been only 1 call made about poisoning. There has been a considerable amount of calls made about fire alarms. Similarly, respiratory emergency calls are also higher, which could indicate the presence of harmful air pollutants in the air in the particular area. Further detailed analysis of these data could help in determining the air quality of the areas where respiratory emergencies are on the higher number. I could also observe that Mondays had the highest number of emergency calls, and Sundays had the least number of calls. As per common assumption, Mondays are usually stressful, and Sundays are the least stressful, which can be concurred from this data as well. While looking at the time of the day, it could be seen that EMS calls are more during the period of 11.00 am and during the period of 3.00 pm to 5.00 pm, which could indicate that these are the most stressful times of the day.  The least number of calls were recorded during the month of November, but it cannot be finalized yet, since the year of 2018 has one more month to go. But based on the existing data, it can be safely predicted that the year of 2018 has comparatively lesser emergencies than the previous years. 
