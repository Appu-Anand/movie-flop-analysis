# 🎬 Movie Flop Analysis

## 📜 Project Overview
This project analyzes why certain movies fail at the box office, specifically focusing on **high-budget** movies that didn’t recover their production costs. Using a dataset of over 5000 movies from TMDB (The Movie Database), we explore how factors like **budget**, **IMDb ratings**, **runtime**, and **popularity** contribute to a movie's financial success or failure.

## 🛠️ Tools Used
- **Python** for data analysis
- **Pandas** for data cleaning and manipulation
- **NumPy** for mathematical operations
- **Matplotlib & Seaborn** for data visualization
- **Jupyter Notebooks** for running the analysis

## 📊 Key Insights
- **Most movies that flopped** had **IMDb ratings below 6**.
- There’s no significant relationship between a movie's **runtime/popularity** and its financial success.
- High **budgets** were a common factor in many of the **biggest flops**, indicating that overspending may have led to greater losses.
- A few notable **high-budget disasters** (e.g., losses exceeding $100M) were identified.

## 📂 Dataset
The dataset used for this analysis is the **TMDB 5000 Movies Dataset** from Kaggle:  
[TMDB 5000 Movies Metadata](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## 📝 Installation & Requirements

### Requirements:
To run this project, you’ll need the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- jupyter

### Installation:
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/movie-flop-analysis.git
    cd movie-flop-analysis
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use: venv\Scripts\activate
    ```

3. Install the necessary libraries:
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter Notebook and run the analysis:
    ```bash
    jupyter notebook
    ```

## 💡 How to Use:
- Open the `movie_flop_analysis.ipynb` Jupyter Notebook to view the full analysis.
- The dataset (`tmdb_5000_movies.csv`) is included, so you can run the analysis on your own machine.

## 📄 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

> ✨ Feel free to explore, fork, and contribute to the project. More improvements and projects will be added in the future!
