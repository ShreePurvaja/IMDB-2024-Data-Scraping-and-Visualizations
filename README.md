# 🎥 IMDb 2024 Data Scraping & Visualization 🎬 

## 🌟 Overview  
This project focuses on **extracting, analyzing, and visualizing** movie data from IMDb for the year **2024**.  
Using **Selenium**, we scrape movie details such as **Title, Genre, Duration, Rating, and Voting**.  
The dataset is **cleaned with Pandas, stored in TiDB Cloud (SQL)**, and analyzed using an **interactive Streamlit dashboard** with **dynamic filters and visualizations**.  

## 🛠️ Tech Stack  
- **🐍 Programming Language**: Python  
- **🌐 Web Scraping**: Selenium  
- **📊 Data Processing**: Pandas,numpy  
- **🗄️ Database**: TiDB Cloud (SQL-based)  
- **📉 Visualization**: Plotly 
- **💻 Web Application**: Streamlit  

## 🎯 Business Use Cases  
✅ **Top 10 Movies**: Identify highest-rated & most-voted movies.  
✅ **Genre Distribution**: Analyze movie counts per genre.  
✅ **Average Duration by Genre**: Find movie length variations by genre.  
✅ **Voting Trends**: Discover genres with the most votes.  
✅ **Popular Genres**: Identify IMDb's **most dominant genres** in 2024.  
✅ **Rating Distribution**: Understand how ratings vary across movies.  
✅ **Genre-Based Rating Leaders**: Find **top-rated** movies per genre.  
✅ **Duration Extremes**: Identify the **shortest & longest** movies.  
✅ **Ratings by Genre**: Compare **average ratings** for each genre.  
✅ **Correlation Analysis**: Explore relationships between **ratings & voting counts**.  

## 🚀 Features  
✔ **🔍 Dynamic Filtering**: Filter movies by ratings, duration, votes & genre.

✔ **📊 Interactive Visualizations**:  
   - 🔝 **Top 10 Movies** by Rating & Voting  
   - 🎭 **Genre Distribution** (Bar Chart)  
   - ⏳ **Average Duration by Genre** (Horizontal Bar Chart)  
   - 🗳️ **Voting Trends by Genre** (Bar Chart)  
   - ⭐ **Rating Distribution** (Histogram/Boxplot)  
   - 🍿 **Most Popular Genres by Voting** (Pie Chart)  
   - 📈 **Correlation between Ratings & Voting** (Scatter Plot)  
   - 🏆 **Genre-Based Rating Leaders** (Table)  
   - 🎬 **Duration Extremes** (Table/Card)  
   - 🔥 **Heatmap for Ratings by Genre**  

## ⚙️ Installation  
### 1️⃣ Clone the Repository  
```bash
git clone https://github.com/yourusername/imdb-2024-analysis.git
cd imdb-2024-analysis
```

### 2️⃣ Install Dependencies
Ensure the following dependencies are installed:

#### -Python 3.12+
#### -pip (Python package manager)

```bash
pip install pandas streamlit selinium numpy mysql-connector-python
```

### 3️⃣ Set Up TiDB Cloud Database
  #### 1.Create a TiDB Cloud account
  #### 2.Load the cleaned IMDb data into the database
  #### 3.Update database_config.py with your connection details

### 4️⃣ Run the Streamlit Application
```bash
streamlit run app.py
```
## 📶Access the dashboard:
### Local URL: http://localhost:8501
### Network URL: http://192.168.29.6:8501
### Note: It might take a few seconds to wake this app up

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
#### 1️⃣ Fork the repository
#### 2️⃣ Create a new branch (feature-new-chart)
#### 3️⃣ Commit changes and push to GitHub
#### 4️⃣ Open a pull request

## 🔗 Additional Resources  
- 📚 **[Streamlit Documentation](https://docs.streamlit.io/library/api-reference)**  
- 🐍 **[Python Documentation](https://docs.python.org/3/)**  
- 🏛 **[SQL Documentation](https://www.w3schools.com/sql/)**  
- 🐼 **[Pandas Documentation](https://pandas.pydata.org/docs/)**  
- 🌐 **[Selenium Documentation](https://www.selenium.dev/documentation/)**

## 📜 License
This project is licensed under the MIT License.

## 👨‍💻 Author
Shree Purvaja D – ✉️ [shreepurvaja@gmail.com]

## 📽️ Check out the project demo below! 👇
-🔗 **[LinkedIn - www.linkedin.com/in/shree-purvaja-d](https://www.linkedin.com/posts/shree-purvaja-d_guvi-datascience-webscraping-activity-7311851269587877889-qBn5?utm_source=share&utm_medium=member_desktop&rcm=ACoAAD6NFTQBzSiBdliy2LKPcwqvdB5nsrx5EKE)**  

### 🚀 If you find this project helpful, give it a ⭐ on GitHub!


