# Webscrapping_List-of-largest-companies
This python project scrapes data of the List of Large companies in US from the public website - Wikipedia equipping pandas, beautifulsoup and requests.

# Execution process
1. Import the packages
2. Call the URL
3. Inspect the webpage for the table and class from the html script and locate the desired data to be scrapped
4. Pull in the Headers/Titles of the desired table after stripping the extra characters
5. Once Titles are generated, convert it into a DataFrame using Pandas
6. Pull in the data from the table which was used to generate titles
7. Loop throught the data to append the row_data one by one to the bottom of the dataframe
8. Convert the dataframe into .csv file and save it to the desired location.
