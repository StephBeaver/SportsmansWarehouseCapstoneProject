For my Capstone Project I did a sentiment analysis on google reviews for Sportsman's Warehouse. The first code is a scraper. It is designed to do multiple URL regions at a time, getting all 148 (stores, gunsmith at Sportsman's and the Distribution Warehouse) stores in
One continuous scarape. It sets up a temporary profile, and runs headless, and at variable speeds in an attempt to make google think it is human. It saves after each store into a temporary folder and keeps track of the URLs for each store. 
This way, if the runtime gets interuppted, you can start where you left off. 

The next code is the one I used to convert the HTML data to a csv. The csv then has the Author of the review, Date the review was left (approximate because google reviews say 2 days ago, 4 weeks ago, 5 years ago etc), star ratings, text review, and the reviewer experience, and I used the store address as the unique ID throughout the analysis. 

Third is the sentiment analysis, which I then followed into an LDA topic modeling. I added categories (departments) and subtopics in an effort to make meaning out of the analysis. Later in the project, I then added annual and quarterly revenue from SEC filings to do a pearson correlation. I also designed a code to extract employees whos names are mentioned in the reviews. 

I then designed a tableau Storyboard with this information. It is interactive with the ability to filter states (which is how I grouped stores) categories, and subtopics. 
