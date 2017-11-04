# Amazon cell phones evaluation platform 

# Abstract

Buying products from Amazon can be risky. Reviews help when making decision which product to buy, as they give users more product details and personal experience. Since everybody who wants to buy a product from Amazon usually spends some time reading the reviews and ratings, we decided to create evaluation platform which would help the users decide by giving them insight into model's downsides and advantages based on the reviews.

This platform will use reviews and extract meaningful information from it, and then evaluate certain product based on these reviews. We will use sentiment analysis to classify each of the reviews (and it's parts) as good or bad. Based on this we will describe each model. Some of the specifications that will be taken into account are the ergonomy, battery, memory, etc. If we have enough time, we will try to see how the reviews changed during the time for each model, or in other words to see if some models improved during the time.


# Research questions
 - Which specifications are mentioned as relevant in the reviews for each of the model?
 - What are downsides and advantages for specific model based on review descriptions?
 - Divide cellphones into groups based on money ranges. Which model is the best choice for each of the groups?Is the exact date and time of the review important? Do some models show signs of improvement during time?

# Dataset
Amazon dataset (Cell Phones and Accessories). This dataset contains from k-core .json file (data have been reduced to extract the k-core, such that each of the users and items have k reviews each) and from .csv file that presents only ratings. These dataset includes no metadata or reviews, but only (user,item,rating,timestamp) tuples. 

Additional web scraping from Amazon (if at some point decided it is necessary)

# A list of internal milestones up until project milestone 2
 - Understand the data into more details
 - Preprocess reviews using sentiment analysis
 - Present the exploratory data analysis in one notebook
 - Try different machine learning techniques and approaches
 - Think about presenting the final result. How to present the data story, what interesting patterns we found, relations etc.

# Questions for TAa
Which libraries and machine learning techniques are we allowed to use?