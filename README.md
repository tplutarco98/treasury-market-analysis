# Mark-to-Market Analysis of Brazilian Government Bonds 📈

This project aims to analyze the mark-to-market behavior of Brazilian Treasury bonds, identifying periods of appreciation and depreciation based on statistical quartiles. The entire data pipeline was developed in Python using Google Colab, with final visualization performed in Power BI.

## 📌 Objective
To identify, based on historical data from the Brazilian National Treasury, periods of price increase, decline, and stability in government bonds, supporting visual and strategic analysis for investors or academic use.

## 🔧 Technologies Used
- Python (Google Colab)
- Pandas
- Web Scraping (BeautifulSoup)
- Google Sheets API
- Power BI (final visualization)

## 🧱 Project Structure
1. **Data collection**: Web scraping of public price tables from the Brazilian Treasury website  
2. **ETL and transformation**: Data cleaning, transformation, and classification using quartile analysis  
3. **Automated export**: Data pushed to Google Sheets  
4. **Visualization**: Power BI dashboard with filters for bond types, maturity periods, and historical trends

## 📊 Results
- Interactive dashboard enabling historical behavior analysis of bonds  
- Identification of periods of price fluctuation based on statistical models  
- Fully automated pipeline with low computational cost

## 🚀 How to Run
1. Open the notebook `ETL_Tesouro_direto_organizado.ipynb` in Google Colab  
2. Install required libraries (`pip install wget` and `bs4`)  
3. Authenticate your Google account to access Google Drive  
4. Run the cells in sequence  
5. Use the Google Sheets file as a data source in Power BI

## 📁 Data Source
The data is collected directly from the official Brazilian Treasury website. Please verify the page structure before executing the scraping process.

---

**Author:** Tiago Plutarco  
**Contact:** [LinkedIn](https://www.linkedin.com/in/tiagoplutarco)
