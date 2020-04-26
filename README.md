# Web_Scraping_Python
Scrape data from Board Game Geek page

Web page Link I want to scape data: https://boardgamegeek.com/browse/boardgame

Objectives: Scrape data from Board Game Geek page and persist it as a partitioned Parquet table named games.board_games. 
  Use the current date as the partitioning field.
  
What did I do in this file?
Apply BeautifulSoup and urllib package in Python to scrap data


Part of the outcome:

Rank|           Image_URL|               Title|Year_Published|GreekRating|AvgRating|NumVoters|CurrentDate|
+----+--------------------+--------------------+--------------+-----------+---------+---------+-----------+
|   1|https://cf.geekdo...|          Gloomhaven|          2017|      8.578|     8.84|    33632| 2020-03-28|
|   2|https://cf.geekdo...|Pandemic Legacy: ...|          2015|      8.467|     8.62|    36093| 2020-03-28|
|   3|https://cf.geekdo...|   Terraforming Mars|          2016|      8.271|     8.42|    51931| 2020-03-28|
|   4|https://cf.geekdo...|   Brass: Birmingham|          2018|      8.251|     8.63|    11837| 2020-03-28|
|   5|https://cf.geekdo...|Through the Ages:...|          2015|      8.225|     8.48|    19204| 2020-03-28|
|   6|https://cf.geekdo...|Twilight Imperium...|          2017|      8.195|     8.69|    10299| 2020-03-28|
|   7|https://cf.geekdo...|   Twilight Struggle|          2005|      8.155|     8.31|    37457| 2020-03-28|
|   8|https://cf.geekdo...|Star Wars: Rebellion|          2016|      8.155|     8.42|    19809| 2020-03-28|
|   9|https://cf.geekdo...|        Gaia Project|          2017|      8.142|      8.5|    12903| 2020-03-28|
|  10|https://cf.geekdo...| Great Western Trail|          2016|      8.098|     8.28|    24319| 2020-03-28|
|  11|https://cf.geekdo...|              Scythe|          2016|      8.095|     8.26|    49048| 2020-03-28|
|  12|https://cf.geekdo...|War of the Ring (...|          2012|      8.071|     8.46|    11676| 2020-03-28|
