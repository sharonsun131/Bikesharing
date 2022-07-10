# Bikesharing with NYC Citibike Data

## Overview of the statistical analysis:

The purpose of this analysis is to solidify the proposal with a bike trip analysis, so that investors will be convinced that a bike-sharing program in Des Moines is a solid business proposal. 

## Results:

First, we need to change the column Trip Duration from a integer to a datetime datatype to get the time in hours, minutes, and seconds using Pandas function. And then export the DataFrame as a new CSV file without the index column. Here are the revised DataFrame: 

![Screen Shot 2022-07-10 at 9 55 17 AM (2)](https://user-images.githubusercontent.com/102264298/178159104-37002188-c4d8-48ee-8f98-36ab8d0db566.png)

Using the reivised CSV file, seven visualizations for the trip analysis were created.

The graph of Checkout Times for Users shows that almost all bike trips are within 60 mins, and more specifically the majority of the bike trips are within 20 mins.  

![Screen Shot 2022-07-10 at 11 42 44 AM (2)](https://user-images.githubusercontent.com/102264298/178159110-14d3ab63-2353-4ec2-9f60-d16df115de38.png)

The graph of Checkout Times by Genders shows that the pattern is the same regardless of gender, however male users have more rides. 

![Screen Shot 2022-07-10 at 11 23 53 AM (2)](https://user-images.githubusercontent.com/102264298/178159113-4e274651-ce57-4063-a744-2b6b63647e30.png)

The graph of Trip by Weekday per Hour shows that the peak hours of bike riding is 5-6pm on Monday, Tuesday and Thursday. While in the early morning from 7-9am Monday to Friday also have high usage. It is also indicated that the purpose of bikesharing users is mainly for workday commute.  

![Screen Shot 2022-07-10 at 1 07 09 PM (2)](https://user-images.githubusercontent.com/102264298/178159118-67b778d5-358b-42ca-8584-e5ae52ead64c.png)

The graph of Trip by Genders(Weekday per Hour) shows that the pattern is the same regardless of gender, however male users have more rides. 

![Screen Shot 2022-07-10 at 1 20 40 PM (2)](https://user-images.githubusercontent.com/102264298/178159121-6e511d1a-0e4f-4a5b-853d-48431d47e918.png)

The graph of User Trips by Gender by Weekday show that male subscribers are the mainly users and they ride the most on Thursday and Friday. 

![Screen Shot 2022-07-10 at 1 26 39 PM (2)](https://user-images.githubusercontent.com/102264298/178159125-f3bfa55d-d230-4e03-9e68-a894cd641777.png)

The graph of Bike Repairs shows that which bikeid is used the most, the darker the blue means the bike is heavily used and will require possible repair. 

![Screen Shot 2022-07-10 at 2 25 40 PM (2)](https://user-images.githubusercontent.com/102264298/178159199-4eca804d-6aa6-4257-98b0-b23e8f1a9efd.png)

The graph of August Peak Hours shows that the peak time for bikeshring is between 5pm to 6pm in August.  

![Screen Shot 2022-07-10 at 2 25 43 PM (2)](https://user-images.githubusercontent.com/102264298/178159200-6a8b963d-98bc-4418-a337-926e1520ddf8.png)


There is a description of the results for each visualization

## Summary:

### Conclusion

Bikesharing business is a promising industry and riding bike is a healthier life style and also energy saving. It is recommended to implemented in Des Moines. However, a few addtional visulizations may be performed to fully demonstrated the annlysis.  

### Two additional visualizations are suggested for future analysis
  1. It is suggested to make a visualization of the age of the bike users.   
  
  2. Average trip cost and subscriber cost are recommended to be analyzed. 
