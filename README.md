# udacity-data-wrangling

Data Gathering :
The first thing I did, I downloaded twitter_archive_enhanced.csv and opened the Image Predictions

I use the Python Tweepy library and have stored the full JSON dataset for each tweet in a file called the tweet_json.txt file.

Assess data 
After collecting each piece of the above data, I assessed it visually and programmatically regarding the quality and ranking issues.

I have been discovering and documenting eight (8) quality issues and Three (3) tidiness issues

1- Quality: twitter_en Enhanced schedule:

unnecessary columns (in_reply_to_status_id, in_reply_to_user_id, retweet_status_id, retweet_status_user_id, retweet_status_timestamp, source, doggo, floofer, pupper, puppo)
Convert dates in twitter_enhanced timestamp column to date and time object
Values missing in the expand_urls column Issues of values ​​in numerator and denominator columns
Change the data type from object to int for numerator and str for tweet_id Duplicate values ​​for dog names (Lucy, Cooper, Charlie, etc.) There are dogs without names
The dog's name is "A", that's not the correct name

2- The tidiness:
Merging of the three data sets

p1, p2, and p3 columns and their properties (conf, dog) columns in df_image must be combined into one column
Rename name, extended URL addresses and text columns

Cleaning:

I Take a copy of every dataset we have and solve the problems we mentioned in Assess phase

Storing data : 

I Stored the clean DataFrame) in a CSV file named twitter_archive_master.csv.
