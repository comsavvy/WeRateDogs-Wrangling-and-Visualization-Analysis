# **Data Wrangling and Visualization on WeRateDogs Tweets Information**

## **Introduction**
WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though almost always greater than 10, e.g., 11/10, 12/10, 13/10, etc., Why? Because "they're good dogs".

WeRateDogs has over 4 million followers and has received international media coverage.

Since real-world datasets rarely come clean, I will be using Python and its libraries to gather data from a variety of sources and in a variety of formats, assess its quality and tidiness, and then clean it. This is called **data wrangling**!

## **Data description**

**Twitter archive**: The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column in the archive does contain each tweet's text where ratings, dog name, and dog stage (i.e., doggo, floofer, pupper, and puppo) were extracted. To make this Twitter archive enhanced, out of the 5000+ tweets, only those with ratings were filtered (2366).

**Image prediction**: Every image in the WeRateDogs Twitter archive was classified into different breeds using a neural network algorithm. The results: a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4, since tweets can have up to four images).

**Additional tweet data**: Additional tweet information will be acquired from Twitter to address and bring out various insights on WeRateDog tweets, such as the number of likes and retweets, etc.

## Analysis
Kind click [here](https://github.com/comsavvy/WeRateDogs-Wrangling-and-Visualization-Analysis/blob/main/wrangle_act.ipynb) to see the analysis. 
Enjoy!
