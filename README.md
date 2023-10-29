# linkedin job scraper

This is the LinkedIn job scraper to scrape job information on the Finnish job market.

### About scarper.ipynb:

The scraper is able to extract information including "company", "job title", "job level", "location", "employment type", "job function", "industry", "posting language", "required working language" and so on. 

The scraper will first generate a list of job IDs "jobid.txt" and then remove the duplicates (which needs further work if necessary) so we have "jobid_cleaned.txt"

Then it will print the raw information in the dictionary to the file "rawinfo.txt".

The hard coded information such as "company", "job title", "job level" etc., will be retrieved from html data.

<img width="2364" alt="Screenshot 2023-09-09 at 16 34 26" src="https://github.com/chaowang0524/linkedin_scraper/assets/85655614/76a13d22-cb6b-43d9-9d70-a8d14bbb6a8d">

### Update on 05-Oct:

The analyser will send the content in "Job Description" block to ChatGPT API to analyze the information including "Skill Required", "Language Requirement", "Start time and duration" and "Salary"

In the end, the dictionary will be converted into "result.csv" for further analysis and visualization.



### TODO: 
1. Considering to add the salary info to predict the salary in future.
2. Considering to scrape job information related to AI/NLP/ML/DS on EU and UK job market and analyse.
