## Digital Democracy Project Contributions

This repository is dedicated to suggesting contributions to the Digital Democracy Project. The repository is going to be dedicated to implementing AI functionality to the project, mostly in Python. 

The 'Democracy_Project.ipynb' file is a notebook file that includes teh start of a pipeline that extracts relevant information from the official Florida Senate Website FLSenate.gov, and manipulate the data to fit the needs of the Digital Democracy Project. 

### Current Features Added:

1) Extracting Bill Information from Webpage: This notebook data mines the bill information directly from the Florida Senate Website. I see that the website is structured where there is a specific format for the URLs and the last part of the URL contains the specific bill in question. By providng the URL for the bill, this code is able to extract the relevant info.
2) Downloading the Bill Information for Analysis: This code below downloads the PDF of the bill and extracts the texual information needed for summarization.
3) Summarizing Each Page of the Bill with OpenAI API: This feature is able to use the .PDF extracted in the file directory. Then, it calls the OpenAI API to summarize each page and print the summaries to make it easier for the staff at the Digital Democracy Project to summarize the bills for the users of the app

### New Features to be Added:

1) Create Multiple Translations of Bills & Summaries
2) Create Pro's and Con's for each bill using OpenAI API
3) Generate a better format for each bill that includes all relevant information for each bill
4) Create a user interface that is easy to use for people at the Digital Democracy Project.