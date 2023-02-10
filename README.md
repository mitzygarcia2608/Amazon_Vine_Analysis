# Amazon_Vine_Analysis
# Overview
In this project, we will have to choose a dataset and use PySpark to perform the ETL process, and load the data into pgAdmin.  From there, we will use Pandas to determine if there are any biases in reviews when comparing unpaid Amazon reviews vs Amazon Vine (paid) program members.  For this analysis, we chose to review video games.
Results

•	How many Vine reviews and non-Vine reviews were there? 
![image](https://user-images.githubusercontent.com/111592990/218219463-f9216646-3910-4375-82e7-efc91fd885b7.png)

![image](https://user-images.githubusercontent.com/111592990/218219489-94591324-0404-4258-a66b-5fdbe670233e.png)

•	How many Vine reviews were 5 stars?  How many non-Vine reviews were 5 stars?

![image](https://user-images.githubusercontent.com/111592990/218219526-e6d929fc-700a-4a8e-8f22-236e4ace7fc8.png)

![image](https://user-images.githubusercontent.com/111592990/218219548-e53f7972-eefc-4e96-aae0-98c0de51370a.png)

•	What percentage of Vine reviews were 5 stars?  What percentage of non-Vine reviews were 5 stars?

![image](https://user-images.githubusercontent.com/111592990/218221603-d7b9c516-0d81-44a5-973b-a875f0c40100.png)
![image](https://user-images.githubusercontent.com/111592990/218221619-36c3dc3d-38f6-481d-9934-94e2fcd96aac.png)

# Summary
After concluding the analysis, the results show that Vine reviews were giving 5 star reviews 51% of the time.  Conversely, the unpaid reviews gave 5 stars 39% of the time.  Thus, we can determine that there is a positive bias in positive reviews for Vine members. 
An additional analysis which can be conducted would be to compare the other star levels of the reviews.  For example, is there a bias in 2 star reviews, 3 star reviews, etc?
