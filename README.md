While it´s very impressive that today's technology allows us to gather incredible amounts of data, the reality is much of this data is currently collected before anyone answers: “What do we want to do with this data?" The result: WPP has a lot of data and people don´t know about it.

For this challenge, we have worked with a concept always on mind: **Data for business.** What does this mean? Easy, it means that we are going to work in a dashboard where people, who are not used to working with data, understand all the data that WPP has available.

As we said, our objective (and the objective of this challenge) is to create an easy and useful dashboard, but also a dashboard that is always updated, now with 276 datasets and in one year from now with 3.000 of datasets. The dashboard must be updated easily and fast to make all the data accessible to all the WPP Group. 

#### Challenge topics

- **Insigths:** Clear insights are very important. To understand in an easy way what data WPP has and if it is useful for anyone who arrives at our dashboard, we try to look for insights that are not readily visible and answer questions like when or where.
- **Visualization:** We decided to use DataStudio because it is very easy to connect to multiple platforms and it fits perfectly with the dashboard we want to develop. 
- **Comprehensiveness:** Interesting insights but easy to understand with clear and direct charts that are updated when a new dataset is uploaded.
- **NLP Approach:**
- **Code:** All the code has been developed to be usable and to let us have the dashboard always updated. We have used the dataset of url-collection-topic as a starting point. From there, we use the urls to extract all the metadata from the dataset and work with it. After you add a new dataset to this dataset, you only have to execute the code to have the dashboard fully updated. 

#### What have we done? 
The final objective is to have a good dashboard, but before having it ready, we need to understand what we have.
We connect with the API and the dataset with all the URLs to export all the metadata and we start to work with it creating 5 final dataframes.
1. **Countries.** Dataset titles and all the countries inside the summary text.
2. **Dates.** Dataset titles and all the dates inside the summary text. When we detect a range (for example from 2000 to 2020) we include all the dates inside the range.
3. **Tags.** Dataset titles and all the dates of each one. 
4. **Full data.** Dataset with all the info from the metadata. From title to collection, privacy, description... 
5. **Resume.** A resume of what we have, how many datasets? How many countries? When have we got data from? 

#### The Dashboard

You can access our dashboard here: http://bit.ly/WPP_Challenge
What are you going to find on it? 
- **Updated date.** Every time the code runs the date is updated.  

![](http://digitalworldtrends.com/Data_Studio/Images/000.png)
- **Quick insights,** because it is very interesting to understand how big is the data from WPP. 

![](http://digitalworldtrends.com/Data_Studio/Images/001.jpg)
- **Charts**, the objective of these charts is to show very fast all the categories and what data is available from WPP.
World map with what countries are included in our datasets.
Sunburst to review the collections and topics.
Timeline with the years about we have data.
Word Cloud with a quick overview of the tags of all the datasets.

![](http://digitalworldtrends.com/Data_Studio/Images/003.jpg)

- **Data table**, after reviewing the different options that you can filter the data, it is time to go deep in, now with the data table the user can filter all the datasets from collection, topic, country and year and access to the dataset. 

![](http://digitalworldtrends.com/Data_Studio/Images/004.jpg)

**The Team**, last but not least :stuck_out_tongue_winking_eye: we are the team who have been involved in this amazing Data Challenge and we hope you are happy with the result.

![](http://digitalworldtrends.com/Data_Studio/Images/team.jpg)








