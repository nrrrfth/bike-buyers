# **Bike Buyers Dataset**

Analysis bike buyers based on my personal project

## **Background**

The project that I did which I used as an exercise to improve my analytical skill in the field of data analyst

The purpose of this project is to see how the features listed in the data affect the customer's decision to buy a bike

## **Data Collection**
this dataset consist of various features related to the factors that influence the customer's decision to buy a bike

these features include the following:
1. ID
2. marital status
3. gender
4. income
5. children
6. education
7. occupation
8. home owner
9. cars
10. commute distance
11. region
12. age
13. purchased bike

## **Dataset Source**
I got this bike purchases analysis from one of the YouTube data analyst channels which is studying Excel, then I tried to do further analysis using SQL and Python and data visualization using Power BI.

## **Exploratory Data Analysis**

### **Analysis using Excel**
The initial stage of the data analysis is to perform data cleansing using Excel, which I often use Google Sheets for. The first thing I do is remove duplicates from the data so that the data is clean and ready to be used for further analysis. When viewed from the data, there is nothing else to clean, because there are no nulls or empty data, or data that does not match.

### **Analysis using SQL**

I created a new tabble for the bike purchase analysis data

```sql
CREATE TABLE bike_buyers
(  ID integer,
   marital_status varchar,
   gender varchar,
   income float,
   children integer,
   education varchar,
   occupation varchar,
   home_owner varchar,
   cars integer,
   commute_distance varchar,
   region varchar,
   age integer,
   purchased_bike varchar
)
```
