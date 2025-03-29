# 🎥 IMDb 2024 Data Scraping & Visualization 🎬  
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Set Up TiDB Cloud Database
  1.Create a TiDB Cloud account
  2.Load the cleaned IMDb data into the database
  3.Update database_config.py with your connection details

### 4️⃣ Run the Streamlit Application
```bash
streamlit run app.py
```

## 📂 File Structure
```bash
📂 imdb-2024-analysis
├── 📂 data                    # Raw & cleaned datasets
├── 📂 scripts                 # Web scraping & data processing scripts
│   ├── scraper.py             # Selenium-based IMDb scraper
│   ├── data_cleaning.py       # Cleaning & merging IMDb data
│   ├── db_insertion.py        # Inserts data into TiDB Cloud
├── 📂 app                     # Streamlit dashboard
│   ├── app.py                 # Main Streamlit application
│   ├── visualizations.py      # Plotly charts & graphs
│   ├── filters.py             # Filtering logic for user input
├── requirements.txt           # Python dependencies
├── README.md                  # Project documentation
```

## 🎛️ Usage
  🔍 Find Your Movie: Search and filter movies based on rating, genre, votes, and duration.
  
  📊 Overall Analysis: Explore IMDb 2024 movie trends with charts and graphs.
  
  🎛️ Filtered Analysis: Apply dynamic filters to analyze specific movie categories.

### 📊 Dataset
  ✅ Scraped IMDb data for 2024 movies, organized genre-wise.
  📌 Columns Included:
  
  -🎬 Movie Name
  -🎭 Genre
  -⭐ Ratings
  -🗳️ Voting Counts
  -⏳ Duration

## 🤝 Contribution
We welcome contributions! Follow these steps:
1️⃣ Fork the repository
2️⃣ Create a new branch (feature-new-chart)
3️⃣ Commit changes and push to GitHub
4️⃣ Open a pull request

## 🔗 Additional Resources  
- 📚 **[Streamlit Documentation](https://docs.streamlit.io/library/api-reference)**  
- 🐍 **[Python Documentation](https://docs.python.org/3/)**  
- 🏛 **[SQL Documentation](https://www.w3schools.com/sql/)**  
- 🐼 **[Pandas Documentation](https://pandas.pydata.org/docs/)**  
- 🌐 **[Selenium Documentation](https://www.selenium.dev/documentation/)**

## 📜 License
This project is licensed under the MIT License.

## 👨‍💻 Author
Created by [Shree Purvaja D] – ✉️ [shreepurvaja@gmail.com]

🚀 If you find this project helpful, give it a ⭐ on GitHub!


