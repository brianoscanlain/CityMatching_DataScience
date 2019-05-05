# CityMatching_DataScience
Python toolbox which compiles a dataBase of placenames and matching functions for filtering of addresses

The TownsDataBase.py is a module acts as a standalone & portable API for matching addresses. The API relies 
on a knowledge map (obtained from geonames & wikipedia webpages as well as manually-inputted aliases) and
string-matching metrics (using sequence matching [from difflibs] and levenshtein distancing [from fuzzywuzzy])

city-name queries can be matched with this API, and if matching is successful (determined using a threshold 
matching metric) then additional placename metadata can be added (introducing added value to the initial query).

