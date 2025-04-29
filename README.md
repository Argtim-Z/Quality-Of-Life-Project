# Quality of Life Cost Comparison

This project collects cost of living, rent, salary, and quality of life data for selected cities using web scraping, external APIs, and stores it in a MySQL database. The results are visualized with Power BI.

## 🔧 Technologies Used

- Python (web scraping, data processing)
- MySQL (data storage)
- Power BI (visualization)
- APIs used:
  - Numbeo (scraping)
  - ExchangeRate-API (currency conversion)
  - OpenWeatherMap (temperature)

## 📁 Project Structure

- `scripts/scraper.py` – Full scraping + processing pipeline
- `sql/schema.sql` – SQL to create the `city_stats` table
- `data/sample_data.csv` – Sample data 
- `Power BI dashboard` – Shown on [my website](#)

## 🚀 How to Run

1. Clone the repo  
   ```bash
   git clone https://github.com/your-username/quality-of-life-project.git
   cd quality-of-life-project
