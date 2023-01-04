# web-scraping-challenge

#### The challenge was to use two different websites to obtain news articles and weather for the planet Mars and store the data in a usable format for further analysis.
--

## Mars News
--
#### Text was scraped from [Red Planet Science](https://redplanetscience.com) using Splinter, ChromeDriver, and Beautiful Soup. Each headline and article preview was stored in a dictionary and placed in a list. The list of articles was exported to MongoDB, a NoSQL database.
--

## Mars Weather
--

#### Mars weather was accessed at [Mars Temperature Data Site](https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html) using the Splinter and ChromeDriver libraries. The data in the table was scraped using Beautiful Soup. Table data was saved in a Pandas DateFrame. Basis analysis was completed, looking at the numbe of months in the Martian calendar, the total number of Martian days with recorded data, aveage minimum temperatures by month, and assessing the number of Earth days in a Martian year. The number of Earth days in a Martian year was estimated by looking at peak-to-peak temperatures.



