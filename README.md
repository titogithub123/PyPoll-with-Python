# PyPoll-with-Python
## Analyzing Election Results in the State of Colorado.
### Overview of Election Audit
The purpose of the analysis was to determine the results of a recent election in three specific counties in the State of Colorado. We were able to implement our new found skills using the python programming language to run calculations and iterate over our raw data to determine a few of the following metrics. 

```
- The voter turnout for each county.
- The percentage of votes from each county out of the total count.
- The county with the highest turnout.
```

In addition, thanks to the work that we have completed we were also able to determine the ultimate winner of the election, taking into account the winning vote count and also the winning percentage. 

### Election Audit Results
1. One of the very first calculations we wanted to determine was the amount of total votes cast in the election. Based on this information we would then be able to dive deeper into the data to determine the rest of the metrics we wanted to answer. In order to make our work as efficent as possible we used a 'For' loop to iterate over the data and add together all the ballots cast. 

![image](https://user-images.githubusercontent.com/93171738/147887518-b7b24c9d-1420-4aa1-90ac-d4bf4634d317.png)

Here we can see how we used our code to loop over the data to retrieve the total vote count.

2. Secondly, we wanted to have a good understanding of how the votes were broken down by each county, specifically and ultimately we wanted to determine which county recived the highest number of votes. In order to do that we had to collect the total vote count and subdivide it by county. In the code below we can see how we used our python skills to determine how the votes broke down per county. 

![image](https://user-images.githubusercontent.com/93171738/147887661-65da366a-ec42-46c8-8301-8bf163efc2ff.png)

3. By determing the total vote count per county we were able to easily extract which county recieved the highest number of votes. As we could imagine, it was no surprise to see that the county of Denver was the county that recieved the highest number of votes. 

![image](https://user-images.githubusercontent.com/93171738/147887721-70deeab8-9f3e-4c88-9140-9bdf1171fa13.png)

As it turns out the percentages of votes cast per county was not even very close with 'Denver' taking approx. 83% of the total votes cast.
