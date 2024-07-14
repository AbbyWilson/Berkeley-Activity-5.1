Problem Statement: 


The problem that we wanted to investigate was what hypothesis we can find about drivers who accepted a coffee house coupon. Below, there are some interesting visualizations that I used to find specific features and then dig into those further with calculations.


Link to Jupyter Notebook: 


Process & Visualizations:


Based on what I know about Coffee Houses, I chose some columns that I think may be correlated to acceptance rate and explore the data to see whether it is true. The columns I want to investigate are:
* Info about the drive (destination, direction_same, passanger)
* Weather (weather, temperature)
* Demographics (gender, age, income)
* Been to coffee house before (CoffeeHouse)


You can see all of the corresponding histograms in the ‘data visualizations’ folder. From looking at these visualizations, I had a few findings that are all included inline in the jupyter notebook. For ease of reading, I will not include those all here, but the important part was that these data visualizations helped me select 4 groups to focus on: 


* Going to no urgent place + having friends in the car vs. all others
* Going to home/work and being alone in the car vs. all others
* Hot temperature days vs. all others
* Going to coffee house 1+ times vs. all others


From there, I performed calculations on each of these groups to come up with my final findings. The exact process can be found in the jupyter notebook linked above.


Final findings: 


Based on my calculations, I have found that drivers who are not going to an urgent place and have friends in the car is 1.3X higher than all others. The acceptance rate of drivers when the temperature is hot is 1.2X higher. The acceptance rate of drivers who are going to work or home and are alone is 1.5X lower than all others. And the acceptance rate of drivers who have been to a coffee house one or more times is 1.9X higher than all others.


What this means is that for drivers who have accepted the coffee house coupon, we can hypothesize that they are more likely to have been to a coffee house before and are more likely not going to work or home and alone. They are also more likely to not be going to an urgent place and it is slightly more likely that the day was warm.


Next Steps:
The next steps/actions, I recommend that we take are:
* Dig into the other coupon groups to do a similar analysis
* Make changes in terms of who we are sending these coupons to, based on observations like the ones above. For example, we could only send Coffee House coupons to people who had been to one before
* Additionally, and if resources are available, instead of hand picking some features - we could put these features into a machine learning model to try to predict a driver's likelihood of acceptance and only send the coupon if it is above some agreed upon threshold.
* Either way, a few months after making this change(s), let's regather the data and do a pre/post analysis to see if we were able to meaningfully increase the acceptance rate. At that time, we can also re-perform this analysis to continue to fine tune the data