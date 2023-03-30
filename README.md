## Webscraping

1. Navigate to https://www.billboard.com/charts/hot-100/. Using BeautifulSoup, extract out the This Week, artist, song, Last Week, Peak Position, and Weeks on Chart values into a pandas DataFrame.

2. After getting the code working for the current chart, navigate to last week's chart. Notice how the url for the page changes. Write a function which will, given a date, return a pandas DataFrame containing the Billboard chart data for that date.