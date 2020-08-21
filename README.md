![](http://digitalworldtrends.com/Data_Studio/Images/texto_circulosmorados-wpp_readme.jpg)

![](https://img.shields.io/badge/Company-WundermanThompson%20Spain-blue) 

![](https://img.shields.io/badge/Team-FelipeMoreno&JavierCarmona-blueviolet)

![](https://img.shields.io/badge/Python-v3.7-red) 

------------
While it´s very impressive that today´s technology allows us to gather incredible amounts of data, the reality is much of the data is currently collected before anyone answers: “What do we want to do with this data?" The result: WPP has a lot of data and people don´t know about it.

For this challenge we have worked with a concept always on mind: **Data for business.** What this means? Easy, means that we are going to work in a dashboard where people who is not used to work with data understand all the data that WPP have available.

As we said, our objetive (and the objetive of the challenge) is to create an easy and usefull dashboard, but also a dashboard always updated, now with 276 datasets and in one year from now with 3.000 of datasets, the dashboard must be updated easy and fast to make all the data accesible to all the WPP Group. 

#### Challenge topics

- **Insigths:** Clear insights are very important, understand in a easy way what data WPP have and if it is usefull for the anyone who arrive to our dahsboard, we try to look for insights  that are not readily visible and answer to questions like when o where.
- **Visualization:** We decided to use DataStudio because it is very easy to connect to multiple platforms and it fits perfect with the dashboard we want to develope. 
- **Comprehensiveness:** Interesting insights but easy to understand with clear and direct charts that were updated when a new dataset were uploaded.
- **NLP Approach:**
- **Code:** All the code was beed developed to be usable and let us to have the dashboard always updated. We have used the dataset of url-collection-topic as starting point, from there, we use the urls to extract all the metadata from de dataset and work with it. After you add a new dataset to this dataset you only have to execute the code to have the dashboard full updated. 

#### What have we done? 
The final objetive is to have a good dashboard, but before have it ready we need to understand what we have.
We connect with the API and the dataset with all the URLs to export all the metadata and we start to work with it creating 5 final dataframes.
1. **Countries.** Dataset titles and all the countries inside the summary text.
2. **Dates.** Dataset titles and all the dates inside the summary text. When we detect a range (for example from 2000 to 2020) we include all the dates inside the range.
3. **Tags.** Dataset titles and all the dats of each one. 
4. **Full data.** Dataset with all the info from the metadata. From title to collection, privacy, description... 
5. **Resume.** A resume of what we have, how many datasets? How many couentries? from when have we got data? 

#### The Dashboard

You can access to our dashboard here: http://bit.ly/WPP_Challenge
What are you goind to find on it? 
- **Updated date.** Every time the code run the date were updated.  

![](http://digitalworldtrends.com/Data_Studio/Images/000.png)
- **Quick insights,** because is very intereting to understand how big is the data from WPP. 

![](http://digitalworldtrends.com/Data_Studio/Images/001.jpg)
- **Charts**, the objetive of this charts are show very fast all the categories and what data is available from WPP.
World map with what countries are included in our datasets.
Sunburst to review the collections and topics.
Timeline with the years about we have data.
Wordclud with a quick overview of the tags of all the datasets.

![](http://digitalworldtrends.com/Data_Studio/Images/003.jpg)

- **Data table**, after review the different options that you can filter the data it is time to go deep on in, now with the data table the user can filter all the datasets from collection, topic, country and year and access to the dataset. 

![](http://digitalworldtrends.com/Data_Studio/Images/004.png)

**The Team**, last but not least :stuck_out_tongue_winking_eye: we are the team who were been involved in this amazing Data Challenge and we hope you were happy as us with the result.


![](http://digitalworldtrends.com/Data_Studio/Images/team.jpg)








