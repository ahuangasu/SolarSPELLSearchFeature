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
6. Copy the url visible in the terminal and paste it within the data.service.ts file from the services folder in the solarSPELL application; example below:

![image](https://user-images.githubusercontent.com/91769429/218340905-ce2c9ec9-157d-49a8-95b7-b8932189b57b.png)
7. Set up the solarSPELL application on your system following the linked document: (https://docs.google.com/document/d/1ny5iWBWim86duDMJhbsSSVSrJv98NIUpGRZmZF3TlqY/edit?usp=sharing)
8. Open XAMPP and start the Apache Server:

![image](https://user-images.githubusercontent.com/91769429/218341078-c43a3039-5b2b-4ca6-b31a-5e9f8eaf0c24.png)
9. Open a new command prompt and navigate into the solarspell-app folder, then run “ng serve”
10. Open your browser and go to http://localhost:4200, you should be able to see the SolarSPELL application there
