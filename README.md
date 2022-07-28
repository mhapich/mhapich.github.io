# Michelle Hapich's Portfolio

# Project 1: Cruelty-Free Company List
## [Cruelty Free Cosmetic Brands](https://github.com/mhapich/cruelty_free_products.git)

- This notebook pulls the latest list of cruelty-free brands from the website [Logical Harmony](https://logicalharmony.net/cruelty-free-brand-list/).
- Additional information about each brand includes whether it is vegan, if it is black-owned, and if its parent company is also cruelty-free
- After scraping the products from multiple pages, I cleaned the data and put it into a dataset that I uploaded to [Kaggle](https://www.kaggle.com/datasets/mhapich/crueltyfree-brands)
- This dataset has maintained an over 10% download per view ratio, being downloaded at least once every day since being published.

Tableau dashboard with some insights:
<div class='tableauPlaceholder' id='viz1658966120376' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cr&#47;CrueltyFreeProducts&#47;CrueltyFreeDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='CrueltyFreeProducts&#47;CrueltyFreeDashboard' /><param name='tabs' value='yes' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Cr&#47;CrueltyFreeProducts&#47;CrueltyFreeDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1658966120376');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.minWidth='840px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='610px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.minWidth='840px';vizElement.style.maxWidth='100%';vizElement.style.minHeight='610px';vizElement.style.maxHeight=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.minHeight='2300px';vizElement.style.maxHeight=(divElement.offsetWidth*1.77)+'px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>



<span style="color:#630718">Exploring the cruelty-free companies:</span>

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

