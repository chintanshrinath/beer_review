# beer analysis

Following operation are performed on the 'Beer Data'

The columns are

beer_ABV	beer_beerId	beer_brewerId	beer_name	beer_style	review_appearance	review_palette	
review_overall	review_taste	review_profileName	review_aroma	review_text	review_time


Questions: 

1.	Rank top 3 Breweries which produce the strongest beers?
2.	Which year did beers enjoy the highest ratings? 
3.	 Based on the user’s ratings which factors are important among taste, aroma, appearance, and palette?
4.	If you were to recommend 3 beers to your friends based on this data which ones will you recommend?
5.	Which Beer style seems to be the favorite based on reviews written by users? 
6.	How does written review compare to overall review score for the beer styles?


Following operations are performed before solved the question

# Import the libraries and Dataset

# Inspecting the dataframe

# Find unique value for few columns to understandd

# Check data type of each column

# Checking missing values analysis, if it is there and drop observation

# Peforming outlier analysis using box plot


1.	Rank top 3 Breweries which produce the strongest beers?

As per column headers, we will use beer_brewerId to get the strongest beers

Moreover, the strongest factor, we can decide beased on **Alcohol by volume (ABV)**, as there is only one factor, present in the dataset.

Therefore, we will use beer_ABV to dervied strongest beers

# Answer 1 As per analysis, we can say that the top 3 breweries are 6513, 736 and 24215  and beer_ABV values 19.22, 13.75 and 12.46 respectively

Question 2 Which year did beers enjoy the highest ratings?

#Answer 2 As there is no specific column that mentioned data and time to derived the answer


# Question 3 Based on the user’s ratings which factors are important among taste, aroma, appearance, and palette?

There are four features on basis of users have rate the beer. These are taste, aroma, apperance and palette

# Answer 3 Based on  the analysis, we can say that review_aroma is important factor amongst the all features

# Question 4 If you were to recommend 3 beers to your friends based on this data which ones will you recommend?

There are many factors on those factors, we can recommend best beer.
Such factors are beer_ABV, review_appearance, review_palette, review_overall, review_taste and review_aroma

# Answer 4 The top 3 beer recommend

1.   AleSmith Speedway Stout - Oak Aged	
2.   Pilot Series Imperial Sweet Stout - Palm Ridge...	
3.   Bees Knees Barleywine	

# Question 5.	Which Beer style seems to be the favorite based on reviews written by users? 

Here, we count total review for each beer style.

Then we take review_overall to find mean for each beer_style category to derive best beer style

# Answer 5 : - As we have derived first count of review text for each beer_style and then we have used overall_rating for each beer_style as mean

So, we now derived there are three main beer_Style we can ask to user to taste

*   American Double / Imperial Stout
*   Russian Imperial Stout
*   Belgian Strong Dark Ale

# Question 6 Which Beer style seems to be the favorite based on reviews written by users? 

First we will count review on basis of beer style.
Then sort the beer style by counts 

In next step, we will retrieved review_overall by each beer style to understand which beer style is favourite brand.

Then we will plot the data on historgram.

As per analysis, we can say that American IPA is one of the best beer style

#Answer 6 As per over all review score against wrtten review,we can say that below are best beer style

*   American Double / Imperial IPA	
*   American Double / Imperial Stout	
*   American Pale Ale (APA)	







