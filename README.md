# 🛍️ Amazon Web Scraper

This project scrapes product data from Amazon (title, price), saves it to a CSV file, and can notify the user via email when the price drops below a specified threshold.

## 📌 Features

- Scrapes product title and current price
- Appends data daily to CSV file
- Email alert when price drops below desired value
- Uses `BeautifulSoup`, `requests`, `pandas`, and `smtplib`

## 📁 Files

- `Amazon Web Scraper Project.ipynb` – Main Jupyter notebook with full logic
- `AmazonWebScraperDataset.csv` – Collected data (optional)

## 💡 Future Enhancements

- Add UI with Streamlit
- Track multiple products
- Visualization using `matplotlib`

---

> 📌 **Note:** This project is for educational purposes. Web scraping must comply with website terms of service.
