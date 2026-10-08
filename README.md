# FIFA Players Dataset – Exploratory Data Analysis (EDA)

##  Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the FIFA Players Dataset using Python.

The analysis focuses on understanding different characteristics of FIFA players, including nationality, wages, height, clubs, and preferred foot.

##  Dataset

**Dataset:** FIFA Players Dataset

The dataset contains information about FIFA football players, including:

* Player Name
* Nationality
* Club
* Wage
* Height
* Preferred Foot

##  Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

##  Analysis Performed

### 1. Country with the Most Players

The analysis identifies the country with the highest number of FIFA players.

This helps understand which country has the largest representation of players in the dataset.

### 2. Top 5 Countries with the Most Players

A bar chart is used to visualize the top 5 countries with the highest number of players.

**Insight:**
A few countries have a much higher number of players compared to others, showing that football player representation is not equally distributed across countries.

### 3. Player with the Highest Wage

The analysis identifies the player with the highest wage in the dataset.

**Insight:**
Players with very high wages are generally among the most valuable and well-known players. Salary can be influenced by factors such as performance, popularity, and club value.

### 4. Wage Distribution

A histogram is created to understand the distribution of player wages.

**Insight:**

* Most players have average or relatively low wages.
* Only a small number of players have very high wages.
* This shows that income among football players is not equally distributed.

### 5. Tallest Player

The analysis identifies the tallest player in the dataset.

**Insight:**
Very tall players are often found in positions such as goalkeeper, where height can be an advantage.

### 6. Club with the Most Players

The analysis identifies the club with the highest number of players in the dataset.

**Insight:**
A club with a large number of players may have a larger squad and greater investment in player development.

### 7. Preferred Foot Analysis

The number of players using their right and left foot is analyzed and visualized using a bar chart.

**Insight:**
Right-footed players are more common than left-footed players in the dataset. Left-footed players are less common, making them relatively rarer.

##  Visualizations

The project includes the following visualizations:

* Top 5 Countries by Number of Players
* Wage Distribution Histogram
* Preferred Foot Bar Chart

##  Project Structure

```text
FIFA-Players-EDA/
│
├── EDA- FIfa Players Dataset.ipynb
├── fifa_data.csv
└── README.md
```

##  How to Run the Project

1. Clone or download this repository.
2. Make sure Python is installed.
3. Install the required libraries:

```bash
pip install pandas matplotlib seaborn jupyter
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook
```

5. Open:

```text
EDA- FIfa Players Dataset.ipynb
```

6. Run the cells to reproduce the analysis and visualizations.

##  Conclusion

This EDA provides a basic understanding of the FIFA Players Dataset by analyzing player nationality, wages, height, club representation, and preferred foot.

The visualizations help identify patterns such as the dominance of certain countries, unequal wage distribution, and the higher number of right-footed players.
