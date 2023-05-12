# An Exploratory Data Analysis on K-pop Groups, Members, and Industry

## About the Project
This project analyzes data about idols, their groups, company, nationality, among others to have an understanding of the K-pop Industry from the 1990s to current times. This analysis will cover gender splits, prominent companies, member retention rates, height, age, and nationality predominance, group longevity by debut year, and other facets of the industry. 

This project utilizes three datasets. First, the all_kpop_idols.csv from Kaggle, contains all the idols, their country of origin, their group affiliation, their birthplace, date of birth, full and stage names, and their gender. The other two are from the kpop database website dbkpop. This is where the datasets for the female (kpop_girlgroups.csv) and male groups (kpop_boygroups.csv) were from. These contained the groups, their member count, date of debut, their company, fanclub name, and their activity status. 

## About the Files
The project contains the [**Jupyter notebook used to scrape the datasets used**](https://github.com/enzopimentel/K-pop-Industry-Exploratory-Analysis/blob/main/kpop_scraper.ipynb), the [**Power BI file**](https://github.com/enzopimentel/K-pop-Industry-Exploratory-Analysis/blob/main/kpop%20analysis.pbix) for the dashboards of the analysis and data, a [**pdf version of the Power BI file**](https://github.com/enzopimentel/K-pop-Industry-Exploratory-Analysis/blob/main/kpop%20analysis.pdf), and the  written report of the analysis as a word file.

The datasets were created in **Visual Studio Code**, using the _Jupyter Notebook_ extension. The Python libraries used were **BeautifulSoup** and **Pandas**. The data was analyzed and visualized in **Power BI**.

## About the Data
### From Kaggle:
It contained 1793 entries representing idols. The dataset included information such as stage name, full name, Korean name, date of birth, group affiliation, nationality, height, weight, birthplaces, other group associations, former groups, gender, and social media usernames.

### From dbkpop (girl groups):
Focused exclusively on girl groups. It comprised 215 entries representing different girl groups and included information such as the group name, abbreviation, Korean name, debut date, company, current member count, original member count, fanclub name, and active status.

### From dbkpop (boy groups):
Focused specifically on boy groups. It consisted of 210 entries representing various boy groups and included information such as the group name, abbreviation, Korean name, debut date, company, current member count, original member count, fanclub name, and active status.
