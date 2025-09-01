# 🎲 BoardGameGeek Data Scraping Project

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue)](https://www.python.org/)  
[![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange)](https://jupyter.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

---

## 📌 Project Overview

This project scrapes board game data from [BoardGameGeek](https://www.boardgamegeek.com) and creates **four CSV files** that form a small database of board games.  

The scraped data includes:  
- ⭐ Ratings  
- 🎲 Game types  
- 👥 Minimum & maximum number of players  
- 💲 Price  
- ✍️ Designers  
- 🏢 Publishers  
- 🎨 Artists  
- ...and more  

**Total pages/board games scraped per CSV file:** ~25,200  

---

## ⚙️ Implementation

- Written in **Python** inside a **Jupyter Notebook**.  
- Uses the following libraries:  
  - [`pandas`](https://pandas.pydata.org/)  
  - [`beautifulsoup4`](https://www.crummy.com/software/BeautifulSoup/)  
  - [`selenium`](https://www.selenium.dev/)  

---

## 🚀 How It Works

1. Opens [BoardGameGeek](https://www.boardgamegeek.com) in a Chrome browser.  
2. Clicks the **sign-in** button.  
3. Enters the user’s credentials.  
4. Scrapes the specified number of pages.  
5. Extracts the information from each game.  
6. Saves the results into structured **CSV files**.  

---

## 💻 Compatibility

- ✅ Tested on **Linux Ubuntu**.  
- 🔄 Should also work on **Windows** and **macOS**.  

---

## 📂 Output

The scraping process generates four CSV files, which together form a small board game database.  


 
