# 🏦 Largest-Banks-By-Assets
A webscraping Project to test my skills and knowledge of reading HTML tags and Working with Beautiful Soup and ETL.

## Note:
This list is based on the April 2024 S&P Global Market Intelligence report of the 100 largest banks in the world. The ranking was based upon assets as reported and was not adjusted for different accounting treatments.[1] Another publication which compiles an annual list of the world's largest banks is The Banker magazine. It publishes a list of the World 1000 Largest Banks every July. Curled from [Wikipedia](https://en.wikipedia.org/wiki/List_of_largest_banks)

Tools used:  
* Jupyter Notebook
* Pandas
* BeautifulSoup

## Steps taken:
* Scraped [Website](https://en.wikipedia.org/wiki/List_of_largest_banks)
* Examined the HTML tags and identified the position of the table i want to work with using the Class. After extracting the table headers(rows) using the appropriate tags, I loaded them into a DataFrame using Pandas.
* To get the columns, I looped through the necessary tags and saved it to the DataFrame.
* After printing the table and observing they were loaded properly. I loaded it into a csv file format.

[CSV File](https://github.com/GI-Jane7/Largest-Banks-By-Assets/blob/main/LargestBank.csv)
