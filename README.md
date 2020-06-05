# Board-games-prediction

This project can be useful for the board games manufacturer who might want to know what types of games people like and which games got the highest ratings.

### Software and Libraries:

    1.pandas
    2.matplotlib
    3.seaborn
    4.sklearn
    5.Python 3
    
### Dataset
Data is a collection of board game information from Board Game Geek.The dataset contains data of Board Games. The dataset has 20 columns.

Dataset : [Board Games Prediction Data](https://www.kaggle.com/centipede148/board-games-prediction-data)

### Images

![](images/.png)<br/>

• The above chart shows the all seven centroids have been plotted on the map.Now these centroids can be really helpful by acting as a hub so whenever a uber recives a request for ride it can check the minimum distance to each of these centroids. 

![](images/.png)<br/>

The dataset is large so only few values are printed. Mainly there are 4 columns and are described as below:

    • Date/Time : The date and time of the Uber pickup
    • Lat : The latitude of the Uber pickup
    • Lon : The longitude of the Uber pickup
    • Base : The TLC base company code affiliated with the Uber pickup



![](images/ut_pic3.png)<br/>

• In the above chart Elbow method is used to find the optimal value of k by fitting the model with a range of values for K.

![](images/ut_pic4.png)<br/>
• Analyzing the data by weekday and Frequency. 

![](images/ut_pic5.png)<br/>
• Analyzing hour and day together using seaborn chart.      



### Key Points
• If we observe the chart properly then we can see that as the sum of squared distance decreases with the number of clusters  increases. After k=6 there is significant reduction. so we can choose 6 or 7 as as the cluster.<br/>
• Predicting new location such as (40.7332,-74.2342) then it is centroid for cluster 2. 
So the new latitude and longitude value 40.7332,-74.2342 should be assigned to the cluster 2 . This will be as distance from the centroid of cluster 2 is minimum. So the uber ride will come closer to cluster 2.

    
## References

    Wikipedia
    Datacamp
    A lot of googling to figure out how to do stuff.    

