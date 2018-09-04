# Scraping be.Indeed.com
This project is to scrape Belgian Indeed for Business Analyst positions

The process has been split in three:
 - Since the job text is not available when directly searching for a job, first I have created a program to scrape the URL of each job position: "Finished URL Parser indeed.ipynb".
 Then I stored them using Excel, removed the duplicates and saved as CSV
  - Next, I created a parser to extract the text from each URL in the csv and save each job position separately.
  It was done by "Finished Text Parser Indeed.ipynb".
  - Later I used Rapidminer to do loop through all documents, ETL and text analysis "Word Counter for Indeed project.rmp"
  as well as created a process to detect the language of the Indeed job offer: "Detect Language using API.rmp"
