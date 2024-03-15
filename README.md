# naruto-api-data

Using the Dattebayo API to extract relevant data and created a data model on how each table will connect with each other, the link can be found below: <br>
https://api-dattebayo.vercel.app/

The above link will give you access to documentation to see how it can be used. You can access the ERD diagram below:
![Untitled](https://github.com/tmich1997/naruto-api-data/assets/142772458/f7b9f367-5be7-48ca-aba0-9fd3715d4813)

So, what did i achieve:

🍥 I used Python (Requests library) to extract information from the API. Only some of the endpoints were paginated so that added a layer of challenge.

🍥 I used Pandas library to transform the data. A lot of work went it to transforming the data. The main goal was that the cleaned data will be accessible and I would create an ERD diagram that would accompany it.

🍥 I was able to get more experience with using Pandas and getting more accustom to using Jupyter notebook within the VS Code environment.

Some of the challenges that I faced was:

⚡ Some of the data on the "tailed-beast" endpoint were incomplete. My first thought was access a wiki and web scrape the data however, it was only three rows of data and it would have been faster if I found the data manually and inserted it. As a result, I manually crated 3-dataframes and then uninoned them to the original data frame.

⚡Another challenge was trying to see how the data can be connected. As a result, after investigating all the endpoint, I only used the ones that I thought could be connected with other tables.
