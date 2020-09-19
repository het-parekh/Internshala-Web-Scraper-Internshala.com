# Web-Scraper-Internshala.com [Python 3.7+]
  >Last Updated on 19/09/2020
  
![Internshala Logo](https://github.com/het-parekh/Web-Scraper-Internshala.com/blob/master/Screenshots/Internshala%20logo.jpg)

### Third Party Libraries Required :
1. requests [To fetch the Url content ]
2. BeautifulSoup4 [Library used for web scraping]
3. xlwt [To export the data to a Excel File with multiple sheets]


### Different filters are available such as :
- Include work from home
- Part-time
- Internships for women
- Internships with job offer
- Starting from (or after)
- Max Duration
- select multiple locations
- select multiple Category
  
### Stores the following data for every internship available based on the selected filters :
- Title
- Company Name
- Category 
- Location
- Duration
- Stripend
- Last Date to apply 
- Number of applicants who have applied
- Skills Required
- Perks Provided
- Number of openings
- Link to that internship

### How to use it :
1. Download or clone the repository
2. Install Required Libraries
3. Run main.py 
4. Provide appropriate input
5. Obtain the excel file in .xls format

### Input Example :
```
Include Work From home?
Include Part-time?
Internships for women?
Internships with job offer?
(Represent your choice with 1-True or 0-False separated by commas such as 1,0,0,1)

1,0,0,0
Enter different categories separated by commas* (Required)
Web Development
Enter different locations separated by commas* (Required)
Mumbai,Delhi
Enter start date in format (yyyy-mm-dd) or leave empty for current date

Enter maximum duration or leave empty for any duration
3
--------------------------------------------------------------------
How many pages you would like to get? Max Pages (16)
2
Different pages on different sheets?(Default: Yes) | 1: No
#Leave empty if Yes 
--------------Scraping Page 1 -----------------
--------------Scraping Page 2 -----------------

1: Add New Sheet
2: Save and Open the file in Excel
3: Save file
4: Discard file and Exit
2
Enter the name of the file
Web_Dev
```
![Excel File 1](https://github.com/het-parekh/Web-Scraper-Internshala.com/blob/master/Screenshots/Screenshot%201.png)
![Excel File 2](https://github.com/het-parekh/Web-Scraper-Internshala.com/blob/master/Screenshots/Screenshot%202.png)



 
