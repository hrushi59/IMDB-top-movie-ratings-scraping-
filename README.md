# IMDB-top-movie-ratings-scraping-
In this project I have scraped IMDB website with top movie ratings

IMDB URL- "https://www.imdb.com/chart/top"
I used BeautifulSoup library.
Also I used requests module for request url.
Then I checked response and got 200 which is good.
I used prettify function which is in BeautifulSoup, so that we can see html in better way to understand.
Then I used find_all function for 'td' class with title column.
I used get_text to parse the movie name.
Again used find_all function for 'td' class with imdb rating column and parse ratings.
Then stored data in Dataframe.
Then finally we convert this DataFrame into csv file by df.to_csv function.


