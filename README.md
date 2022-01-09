This project had been divided into the following phases:
  1. Project Planning
  2. Data Collection
  3. Data Cleaning
  4. EDA (Exploratory Data Analysis)
  5. Building a model
  6. Production
  
Here is a brief description of each of the following steps:
1. Project Planning: The project planning phase involved extensive research into a suitable subject which can be used to build a project. I had an introspective brainstorming session wherein I listed out various relevant topics and sub-topics. The idea of salary prediction stood out based on the decision matrix analysis. 

2. Data Collection: Data was collected from a well known job search website called glassdoor. This scraper could have been made by either using beautiful soup which takes all the HTML data on a page and process data through the same or by using selenium, which is essentially a bot that goes through and clicks on elements of the page and copies the same onto a data frame. The latter approach was used, which fetched different postings based on various criterias. At the end, the scraoer was run to fetch over 1000 job postings. 

3. Data Cleaning: Obviously the data collected was not in the purest divine form, therefore, data was cleaned using various lambda functions (using regex is also an option), in order to obtain a processable form of data. Many fields including salaries, company name, state/ province, company age, job descriptions were cleaned to obtain a processable form of data (eg- using company text, obtained company rating, inferred the age of the company based on the founding date, parsed numbers/ numeric data from the salary, removed rows with corrupted data, etc.)

4. EDA (Exploratory Data Analysis): Analysis on the obtained data was carried out in order to obtain aggregate data based on various categories and factors with a graphical approach to obtain the summary of the main characteristics of the data using graphical analysis and visualization methods. 

5. Building a model: 

6. Production: All the data will be presented on a website which will be created soon. My current plan is to implement the same using react, express, mongoose using various REST endpoints, deployed via Heroku. 

I would like to acknowledge the inspiration and assistance taken from Ken Jee to bring this project to life.
