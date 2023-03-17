# Mars_Data_Scraping
## This project consists of two technical products:
Deliverable 1: Scrape titles and preview text from Mars news articles.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

### Deliverable 1: Scrape news titles and overviews from a Mars News Website.
: *NOTE*: The source link for this deliverable is below:
https://static.bc-edx.com/data/web/mars_news/index.html
#### To complete this deliverable, a Beautiful Soup object was created to extract the text elements from the website.
#### Each title-and-preview pair was stored in a Python dictionary,

### Deliverable 2: Scrape and Analyze Mars Weather Data
#### *NOTE*: The source link for this deliverable is below:
https://static.bc-edx.com/data/web/mars_news/index.html
#### Similarly to the last deliverable, a Beautiful Soup object was created to extract the data elements from the website.
#### However, further data analysis was required in this deliverable and to do so, the scraped data was assembled into a Pandas DataFrame.
#### Each data type was examined for the scraped data to answer the following questions:
How many months exist on Mars?

How many Martian (and not Earth) days worth of data exist in the scraped dataset?

What are the coldest and the warmest months on Mars.

Which months have the lowest and the highest atmospheric pressure on Mars.

#### The following two graphs were used to visualize the data for some of these proposed questions:
![image](https://user-images.githubusercontent.com/120426753/225792471-c9d6d072-4af0-449b-9495-6587bf30ae79.png)
![image](https://user-images.githubusercontent.com/120426753/225792505-7f11ad18-9d76-42f6-882b-524972ece0a5.png)


### The final step was to save the the DataFrame as a .csv file. 
