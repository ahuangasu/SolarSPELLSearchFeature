# SolarSPELLSearchFeature
A program to run a more extensive search over the SolarSPELL database.

The Content FTS project is aimed at improving SolarSPELL’s search feature. When the user types in a query, the search string will first be evaluated for any spelling errors. It will then be lemmatized to look at the variant forms of the search query. Then, the program will perform the search through the database for the query and return a list of results in a json format.
The current search does not support corrective spelling for the search query nor does it provide results for the lemmatized version of the query. The updated search feature addresses those shortcomings by utilizing python libraries. 
