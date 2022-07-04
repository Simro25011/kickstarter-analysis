# An Analysis of Kickstarter Campaigns

## **OVERVIEW OF PROJECT

### **Background

One of Louise’s play Fever came close to it’s funding goal in a short amount of time. Reason why now, she wants to know how other campaigns fared in relation to their launch dates and their funding goals.

### **Purpose

Our goal then is to help Louise in her decision making while using the dataset provided. We will visualize and analyse campaigns outcomes based on their launch dates and their funding goals.

## **Analysis and Challenges

### **Analysis and challenges of Outcomes Based on Launch Date
 
To analyse the outcomes based on Launch Date, we had to filter the dataset and only use the data we needed. In this case we needed to filter campaigns by years and the Parent category “theater”.  We also needed to convert the date created to the proper format. Once done, we were able to associate to the correct field our outcomes and we were able to have our Pivot table. Finally, we created a line chart showing the number of successful, failed, or canceled projects by month. 
The main challenge we dealt with was to make sure to have the correct field in the correct areas (filter, columns, Rows, values) in order to have a pivot table easy to be read and comprehensible. 

https://github.com/Simro25011/kickstarter-analysis/resources/Theater_Outcomes_vs_Launch.png


### **Analysis and challenges of Outcomes Based on Goals

To analyse the outcomes bases on Goal, we had to create a new sheet with the requisite data for the investigation. Let’s remember in order to be precise for our goals we had to know the min and max amount in order to have an amount range for our evaluation. Then our job was then to have Excel through the COUNTIFS function and the filter on the subcategory “Play” to generate for us the Successful, failed and canceled projects. 
The challenge here was to make sure to select the correct data for our analysis and manually double check the total for successful, failed and canceled matched with our manual count on Kickstarter sheet. Why doing it? Just to confirm the logic is good.

https://github.com/Simro25011/kickstarter-analysis/resources/Outcomes_vs_Goals.png










## **Results

### What are two conclusions you can draw about the Outcomes based on Launch Date? 

As a conclusion to our assessment, we can notice within the 3 years span of the campaign (2014-2016). 
*	May and June were the most successful months respectively with 111 and 100 effective campaigns while being the months where we had the most launch campaigns in total (166 and 153).
*	December seems to be the lowest successful month with 37 successful campaigns, 35 failed and 3 canceled for a total of 75 campaigns during that those 3 years. A plausible explanation can be the Christmas Holidays coming and we can see this down trend starting in October.


### **What can you conclude about the Outcomes based on Goals?

We can see on the outcomes based on goals that Campaigns with a target less than $1000 are very successful (76%) while campaigns over $20000 as a goal tend to be less and less popular and reachable.

### **What are some limitations of this dataset?

Some limitations of this dataset were certainly the unclean data when it came to launch at and deadline columns. We also had to filter and separate category and Subcategory.

### **What are some other possible tables and/or graphs that we could create?

Here are some possible tables and graphs that we could create:
* Outcomes based on pledged amount
*	Outcomes based on deadline
*	Goals based on countries 
*	Film & video Outcomes by Launch Date
