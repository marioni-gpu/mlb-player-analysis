# MLB Player Data Analysis

**Author:** Marioni Curlango

## Overview

This project analyzes Major League Baseball (MLB) player data to identify patterns in physical characteristics such as age, height, and weight. The objective is to explore relationships between these variables and examine how they vary across different player positions.

---

## Dataset

The dataset includes the following attributes:

* Name
* Team
* Position
* Height (inches)
* Weight (lbs)
* Age

**Note:** The dataset appears to be outdated, as some players are no longer active. However, it remains useful for identifying general trends and relationships.

---

## Data Cleaning

The dataset required preprocessing due to formatting issues and non-numeric values. The following steps were applied:

* Removed quotation marks from column names
* Converted weight values to numeric format
* Removed rows with missing or invalid data

---

## Key Findings

### Age

* Average age: 28.7 years
* Most players fall between 24 and 30 years

This suggests that MLB players are typically in their peak performance stage, where physical ability and experience are balanced.

---

### Weight

* Most common range: 180–205 lbs
* General range: 160–250 lbs

This indicates a relatively consistent athletic build among players, with some variation in extreme cases.

---

### Height

* Most players are between 72 and 76 inches

This suggests a relatively uniform height range among professional players.

---

### Position Analysis

* Pitchers tend to be taller
* Designated hitters and first basemen tend to be heavier
* Shortstops and second basemen are generally lighter

These differences reflect the physical demands and roles associated with each position.

---

### Correlation Analysis

| Variables        | Correlation |
| ---------------- | ----------- |
| Age vs Height    | -0.07       |
| Age vs Weight    | 0.15        |
| Height vs Weight | 0.53        |

Key insights:

* Age has little to no relationship with height or weight
* Height and weight show a moderate positive correlation

---

## Visualizations

The project includes:

* Scatter plots (Age vs Weight, Height vs Weight, Age vs Height)
* Histograms showing the distribution of age, weight, and height

These visualizations support and validate the patterns observed in the data.

---

## Limitations

The dataset may not accurately represent the current MLB population, as some players and values are outdated. Despite this, it remains useful for identifying general trends and relationships.

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Project Structure

```
mlb-player-analysis/
│── mlb_analysis.ipynb
│── mlb_players.csv
│── README.md
```

---

# MLB Player Data Analysis

**Author:** Marioni Curlango

## Overview

This project analyzes Major League Baseball (MLB) player data to identify patterns in physical characteristics such as age, height, and weight. The objective is to explore relationships between these variables and examine how they vary across different player positions.

---

## Dataset

The dataset includes the following attributes:

* Name
* Team
* Position
* Height (inches)
* Weight (lbs)
* Age

**Note:** The dataset appears to be outdated, as some players are no longer active. However, it remains useful for identifying general trends and relationships.

---

## Data Cleaning

The dataset required preprocessing due to formatting issues and non-numeric values. The following steps were applied:

* Removed quotation marks from column names
* Converted weight values to numeric format
* Removed rows with missing or invalid data

---

## Key Findings

### Age

* Average age: 28.7 years
* Most players fall between 24 and 30 years

This suggests that MLB players are typically in their peak performance stage, where physical ability and experience are balanced.

---

### Weight

* Most common range: 180–205 lbs
* General range: 160–250 lbs

This indicates a relatively consistent athletic build among players, with some variation in extreme cases.

---

### Height

* Most players are between 72 and 76 inches

This suggests a relatively uniform height range among professional players.

---

### Position Analysis

* Pitchers tend to be taller
* Designated hitters and first basemen tend to be heavier
* Shortstops and second basemen are generally lighter

These differences reflect the physical demands and roles associated with each position.

---

### Correlation Analysis

| Variables        | Correlation |
| ---------------- | ----------- |
| Age vs Height    | -0.07       |
| Age vs Weight    | 0.15        |
| Height vs Weight | 0.53        |

Key insights:

* Age has little to no relationship with height or weight
* Height and weight show a moderate positive correlation

---

## Visualizations

The project includes:

* Scatter plots (Age vs Weight, Height vs Weight, Age vs Height)
* Histograms showing the distribution of age, weight, and height

These visualizations support and validate the patterns observed in the data.

---

## Limitations

The dataset may not accurately represent the current MLB population, as some players and values are outdated. Despite this, it remains useful for identifying general trends and relationships.

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

## Project Structure

```
mlb-player-analysis/
│── mlb_analysis.ipynb
│── mlb_players.csv
│── README.md
```

---

## Conclusion
This analysis of MLB player data reveals clear patterns in physical characteristics such as age, height, and weight.

Most players are concentrated between 24 and 30 years old, with an average age of approximately 28.7. This suggests that MLB players are typically in their peak performance stage, where physical ability and experience are balanced.

In terms of weight, the majority of players fall within the range of 180 to 205 lbs, indicating a consistent athletic build across the league. While some players fall outside this range, they represent exceptions rather than the norm.

Height is also relatively consistent, with most players measuring between 72 and 76 inches. This suggests that there is an optimal height range that is common among professional players.

The correlation analysis shows that age has little to no relationship with height or weight, meaning that physical characteristics remain relatively stable across different ages. In contrast, height and weight show a moderate positive correlation, indicating that taller players tend to weigh more.

Additionally, differences between positions highlight how physical attributes vary depending on player roles. For example, pitchers tend to be taller, while positions such as shortstop and second baseman are generally lighter.

Although the dataset appears to be outdated, it still provides valuable insights into general trends and relationships among MLB players.

Overall, this project demonstrates how data analysis and visualization can be used to identify meaningful patterns in sports performance and player characteristics.
