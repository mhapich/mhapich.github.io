# Michelle Hapich's Portfolio

My love of learning and passion for data science continues to motivate me to learn new tools all the time.  Since I am currently a high school math and computer science teacher, I am highlighting some of my accomplishments here to demonstrate the experience I have in this field.

# Project 1: Cruelty-Free Company List
## [Cruelty Free Cosmetic Brands](https://github.com/mhapich/cruelty_free_products.git)

- I created a dataset which contains a list of cruelty-free brands from the website [Logical Harmony](https://logicalharmony.net/cruelty-free-brand-list/).
- Additional information about each brand includes whether its product line is vegan, if it is black-owned, and if its parent company is also cruelty-free
- Other information in the csv includes whether or not the brand is sold at one of five top retailers
- After scraping the products from multiple pages on the Logical Harmony website, I cleaned the data and put it into a dataset that I uploaded to [Kaggle](https://www.kaggle.com/datasets/mhapich/crueltyfree-brands)
- This dataset currently has a 14% download per view ratio, having been viewed over 1100 times and downloaded more than 150 times. It has been downloaded at least once every day since being published.
- There will be a dashboard containing the table of all products along with which retailers (out of five from [Logical Harmony](https://logicalharmony.net/)) sell them.

### Please see my interactive Tableau dashboard: ###
Here, you can search for a brand to find out more about it, or you can filter the lists to only see things like black-owned brands, or brands that have parent companies that do utilize animal testing on other products.
<span style="color:#e60073; font-size: 16px;"><b>[Cruelty-free products interactive tables](https://public.tableau.com/views/CrueltyFreeProducts/CrueltyFreeDashboard?:language=en-US&:display_count=n&:origin=viz_share_link)</b></span>


<span style="color:#630718">Some screenshots of Jupyter notebook explorations done while creating and cleaning the data:</span>

<img src="Assests/Images/black-owned.PNG" width="600">

<span style="color:#630718">Plotly graphs are interactive within the notebook!</span>
<img src="Assests/Images/parent_co.PNG" width="800">

# Project 2: Data cleaning for district students' transcripts

## [Transcript data cleaning](https://github.com/mhapich/transcript_cleaning.git)

- This repo contains only the notebook file used to show the tasks done to find potential problems in data entry in our district's student information system (SIS).  
- There were problems with some data in the SIS that were causing discrepancies in the class ranks.  I assisted the technology supervisor and guidance department in finding these problems.  I exported this notebook as a simple to navigate pdf with notes on students whose information needed changed.
- I had to anonymize student identifiers to publish this notebook.  Because of this, the original csv file containing student names and id numbers is not included in this repo.

<span style="color:#8c150d">Some topics for further analysis...</span>
![EDA](/Assests/Images/EDA.PNG)
![](/Assests/Images/gpa.PNG)
<br>
<span style="color:#8c150d">One of the data entry mistakes:</span>
![Some main findings for admin](/Assests/Images/fix_anomalies.PNG)
<br>

