
# Data Science Job Scrapers (Naukri + Indeed)

This project includes **two automated web scrapers** built with **Python**, **Selenium**, and **Pandas** to extract **Data Science job listings** from:

- [Naukri.com](https://www.naukri.com/)
- [Indeed.com](https://in.indeed.com/)

Both scrapers collect important job-related information and save it into clean **CSV files** for easy analysis.

---

## 📄 Project 1: Naukri.com Data Science Jobs Scraper

### 🔹 Description:
Scrapes **Data Science** job listings from Naukri.com with details like:
- **Job Profile**
- **Company Name**
- **Experience Required**
- **Salary**
- **Location**
- **Job Application Link**

### 🔹 Features:
- Searches for "Data Science" jobs across India.
- Navigates multiple pages.
- Extracts data from each job card.
- Saves the data into a CSV file named: **`jobs_naukri.csv`**.

### 🔹 Libraries Used:
- `selenium`
- `pandas`
- `time`

---

## 📄 Project 2: Indeed.com Data Science Jobs Scraper

### 🔹 Description:
Scrapes **Data Science** job listings from Indeed.com with details like:
- **Job Profile**
- **Company Name**
- **Company Rating**
- **Job Location**
- **Salary**
- **Job Application Link**

### 🔹 Features:
- Searches for "Data Science" jobs across India.
- Navigates multiple pages.
- Extracts job details from the left panel and collects application links.
- Saves the data into a CSV file named: **`jobs_final1.csv`**.

### 🔹 Libraries Used:
- `selenium`
- `pandas`
- `time`

---

## 🛠️ How to Run the Scripts

1. Install required libraries:
    ```bash
    pip install selenium pandas
    ```

2. Download the correct version of [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/) matching your Chrome browser version.

3. Update the **ChromeDriver path** in the script:
    ```python
    path = Service(r'path_to_your_chromedriver')
    ```

4. Run the scripts one by one:
    ```bash
    python naukri_scraper.py
    python indeed_scraper.py
    ```

Each script will generate a **separate CSV file** with the job data.

---

## 📦 Outputs

| Platform | CSV File Name |  
|:--------:|:--------------:|  
| Naukri   | `jobs_naukri.csv` |  
| Indeed   | `jobs_final1.csv` |  

---

## 🚀 Future Enhancements (Optional)

- Scrape additional fields like **job description** or **posting date**.
- Add **exception handling** for dynamic page changes.
- Combine both CSVs into a **single master dataset** for deeper analysis.
- Deploy as a **streamlit app** to search and visualize jobs live.

---

## 🙌 Acknowledgements

- [Naukri.com](https://www.naukri.com/)
- [Indeed.com](https://in.indeed.com/)
- [Selenium](https://www.selenium.dev/)
- [Pandas](https://pandas.pydata.org/)

---

