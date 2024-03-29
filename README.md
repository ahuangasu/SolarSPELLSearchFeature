# SolarSPELLSearchFeature
A program to run a more extensive search over the SolarSPELL database.

The Content FTS project is aimed at improving SolarSPELL’s search feature. When the user types in a query, the search string will first be evaluated for any spelling errors. It will then be lemmatized to look at the variant forms of the search query. Then, the program will perform the search through the database for the query and return a list of results in a json format.

The current search does not support corrective spelling for the search query nor does it provide results for the lemmatized version of the query. The updated search feature addresses those shortcomings by utilizing python libraries. For more information, visit https://docs.google.com/document/d/12vcUJrG87QU80aVGHwgDJWU59V57nsPX5LWAKxGqGTU/edit?usp=sharing

1. Open your command prompt
2. Set up a virtual environment in the directory with the backend files
3. Install all the packages in the requirements.txt file using the command:
  "pip install -r requirements.txt"
4. Run the nltkReq.py file to download all the required nltk packages in the virtual environment using the command:
  “python nltkReq.py”
5. Activate the virtual environment and run the content_fts3.py file using the command:
  “python content_fts3.py” for windows 
  “python3 content_fts3.py” for mac
