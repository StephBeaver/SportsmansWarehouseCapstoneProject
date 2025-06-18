For my Capstone Project I volunteered to do a sentiment analysis on google reviews for Sportsman's Warehouse. These are the final versions of the code as of the end of class. The scraper is designed to do multiple ranges at a time, getting all 148 stores in
One continuous scarape. It sets up a temporary profile, and runs headless, and at variable speeds in an attempt to make google think it is human. It saves intermittently into a temporary folder and keeps track of the URLs for each store as it finishes the store. 
This way, if the runtime gets interuppted, you can start where you left off. 

The next code is the one I used to convert the HTML data to a csv, converting dates, store addresses etc. 

Third is the sentiment analysis, which I then followed into an LDA topic modeling. I added categories (departments) and subtopics in an effort to make meaning out of the analysis. Later in the project, I then added revenue to the mix and moved everything to tableau for 
Presentation. 
