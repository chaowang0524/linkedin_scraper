# linkedin job scraper

This is the linkedin job scraper for the DS class mini-project idea (analyzing the language requirement of the posted jobs located in Finland on Linkedin).

### About scarper.ipynb:

The scraper is able to extract information including "company", "job title", "job level", "location", "employment type", "job function", "industry", "posting language", "required working language" and so on. If we decide to proceed, we can extract more necessary information such as salary.

The scraper will first generate a list of job IDs "jobid.txt" and then remove the duplicates (which needs further work if necessary) so we have "jobid_cleaned.txt"

Then it will print the raw information in dictionary to the file "rawinfo.txt".

In the end, the dictionary will be converted into "result.csv" for further analysis and visualization.

<img width="2364" alt="Screenshot 2023-09-09 at 16 34 26" src="https://github.com/chaowang0524/linkedin_scraper/assets/85655614/76a13d22-cb6b-43d9-9d70-a8d14bbb6a8d">
