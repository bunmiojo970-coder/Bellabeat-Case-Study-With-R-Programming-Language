# Bellabeat-Case-Study-With-R-Programming-Language

# Executive Summary:

This study is an analysis of how people are already using their smart devices and the opportunities for growth for the Bellabeat Leaf Product that it reveals.The Bellabeat Leaf Product connects to the Bellabeat app to track Activity, Sleep and Stress which are the focus of this analysis. Using R, I transformed the datasets and analysed them to pull out key insights and findings. Since the major aim is to maximize profit from quality insights, I recommend that the marketing strategy team implement the following:

1. Using Personalised emails and notifications in the Bellabeat app for users and also recommendations with their health benefits via websites and other marketing media such as social media posts or ads for new or returning visitors. These emails and notifications should include reminders, habits observation, encouragement and healthier habits suggestions.
2. More reminders or notifications should be sent to the users on the Bellabeat app from between 5pm and 7pm to engage in very active steps such as running because it has been observed to have the highest and most consistent intensities in a day. Lesser hours engaged in very active minutes or steps reduces the average calories released.
3. Notifications between 10am to 2pm should also be sent for lighter steps such as strolling as these period had the second largest intensities. This increases daily steps.
4. Notifications or reminders for bed time should also be sent from 10pm lasting till 6pm for optimal 8 hrs sleep in women per day as these are the times observed to have the lowest intensities in a day.
   
# Business Problem:

The general dream of any business is to maximize profit and expand as much as possible. Several columns of information about smart device usage have been provided for us by the Fitbit Fitness Tracker, a public dataset on Kaggle. How do we make the most of that information to find gaps that can be corrected to maximize the profit and also expand the business?

# Methodology:

1. Data Transformation with R Functions and Tools that improved dataset consistency.
2. Data Analysis with Tidyverse, geom_smooth, ggplot and full_join.

# Skills/Tools Used:

R Programming Language: ggplot, tidyverse, head(), colnames(), n_distinct, format(), summary(), geom_smooth(), full_join(), merge(), geom_histogram().

# Results/Key Insights:

The average step total from the dailySteps dataframe was 7638.
The average step total from the hourlySteps dataframe was 320.2. 
The users had an average sedentary minutes of 991.2 from the activity and dailyIntensities dataframe. This is about 16.5 hours which is really high as the average for a day.
The average lightly active minutes for the users was high at 192.8 per day which is ~ 3 hours.
The average total minutes asleep from the sleep dataframe was 419.5. This is ~ 7 hours/day.
The average calories from the hourlyCalories dataframe was 97.39. The average calories from the dailyCalories dataframe was 2304.

Overall, increasing distance, steps(activities, stress) and active minutes increases calories and increasing steps taken decreases minutes asleep.

# Business Recommendations:

To optimise women's health specifically in the areas of stress, sleep and activity using the Bellabeat tracker connected to the Bellabeat app, I recommend that the following should be incorporated into the next marketing strategy by the Chief Creative Officer of the Bellabeat Company (Urska Srsen):

1. Using Personalised emails and notifications in the Bellabeat app for users and also recommendations with their health benefits via websites and other marketing media such as social media posts or ads for new or returning visitors. These emails and notifications should include reminders, habits observation, encouragement and healthier habits suggestions.
2. More reminders or notifications should be sent to the users on the Bellabeat app from between 5pm and 7pm to engage in very active steps such as running because it has been observed to have the highest and most consistent intensities in a day. Lesser hours engaged in very active minutes or steps reduces the average calories released.
3. Notifications between 10am to 2pm should also be sent for lighter steps such as strolling as these period had the second largest intensities. This increases daily steps.
4. Notifications or reminders for bed time should also be sent from 10pm lasting till 6pm for optimal 8 hrs sleep in women per day as these are the times observed to have the lowest intensities in a day.


# Next Steps:

1. Measure emails and texts open and & click rates.
2. Track social media advertisement performance for engagement or positive responses.
3. Train the customers on making the most of the app for maintenance, optimization and also on new features.
4. Further investigation should be carried out with the provision of more relevant data such as gender, increasing the sample size of the data and calories taken in.
