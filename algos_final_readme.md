I wanted to investigate problems with Citibike. I scraped available reviews from the 
apple app store and looked through them to see what the biggest issues were.
It seemed that problems fell broadly into two categories: app and maintenance issues.
This took a lot of cleaning because the app store HTML was complicated and 
I could not scrape reviews individually. I had to scrape them all together and then split them 
into a format that I could turn into rows in a dataframe. Then I had to clean out responses from the 
developers. Finally, I ran a regression to find if problems were related to app or maintenance.  
It seems the regression did a good job of identifying app based issues but could not identify maintanance issues.
I think the dataset calls for further cleaning to allow for sorting by date, which would allow analysis 
by app update and year. For now, I found that the vast majority of issues are a result of the app not working correctly
or not having an intuitive enough interface. Also, users were sometimes angry to see a favorite feature eliminated 
as a result of an update. 