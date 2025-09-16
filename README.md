# 📝 Task 10: Naukri Job Listings Scraper with  Data & Visualization

## 🎯 Objective:
Scrape Data Analyst job listings from Naukri.com, generate a demo dataset with company names and salary ranges, and visualize job distribution across top cities. Optional skill extraction is also included.

## 🛠 Tools used:

- Python: pandas, random, requests, BeautifulSoup, concurrent.futures, tqdm

- Selenium: Dynamic scraping

- Visualization: matplotlib, seaborn

## 🔹 Step 1: Scrape Job Listings

- Tool: Selenium

- Data Scraped: Title – Job title

- Location – Job location

- Link – Job posting URL

## 🔹 Step 2: Summary  

- Total Jobs Scraped : 40

- Top locations : Hyderabad, Bengaluru, Hybrid Bengaluru, Hybrid Hyderabad, Pune
  
- Demand Skill : Python
  
## 🔹 Step 3:  Visuals

- Top 5 Locations Analyzed using Bar-chart

## 🔹 Step 4:  Out Put saved file : naukri_jobs_demo.csv

- file : [naukri_jobs_demoo.csv](https://github.com/user-attachments/files/22371490/naukri_jobs_demoo.csv)

## Techniques:

- Used find_all() or select() to fetch repeated HTML tags

- Extracted text with .text.strip() for clean strings

- Used time.sleep(1–2) between page requests to avoid blocking
