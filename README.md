# DS 201 Final Project — Auto MPG Data Exploration

## Project Description

This project explores the classic **Auto MPG dataset** to analyze fuel efficiency trends in vehicles manufactured between 1970 and 1982. Using Python-based data science tools, the project covers data exploration, cleaning, and visualization to uncover patterns in fuel economy across different car brands, origins, and time periods.

---

## Dataset Used

- **Name:** Auto MPG Dataset
- **Source:** Built-in dataset from the `seaborn` library (`sns.load_dataset("mpg")`)
- **Size:** 398 rows × 9 columns
- **Features:**

| Column | Description |
|---|---|
| `mpg` | Fuel efficiency (miles per gallon) |
| `cylinders` | Number of engine cylinders |
| `displacement` | Engine displacement (cubic inches) |
| `horsepower` | Engine horsepower |
| `weight` | Vehicle weight (lbs) |
| `acceleration` | 0–60 mph acceleration time (seconds) |
| `model_year` | Model year (70–82, representing 1970–1982) |
| `origin` | Region of manufacture (usa, japan, europe) |
| `name` | Vehicle make and model |

---

## Tools Used

- **Python 3** — Core programming language
- **Pandas** — Data manipulation and cleaning
- **Seaborn** — Dataset loading and statistical plots
- **Matplotlib** — Data visualization
- **Jupyter Notebook** — Interactive development environment

---

## Key Insights

1. **Japan and Europe outperformed the USA in fuel efficiency** — Throughout 1970–1982, Japanese and European vehicles consistently achieved higher average MPG than American vehicles.

2. **Fuel efficiency improved significantly over time** — Average MPG across all vehicles rose from ~17 MPG in 1970 to ~32 MPG by 1982, reflecting industry adaptation to the oil crises of the 1970s.

3. **Heavier vehicles are less fuel efficient** — A clear negative correlation exists between vehicle weight and MPG; lighter cars consistently achieved better gas mileage.

4. **Top fuel-efficient cars were 4-cylinder and lightweight** — The highest MPG vehicles were small, 4-cylinder cars primarily from Japan and Europe.

5. **The least fuel-efficient cars were 8-cylinder American models** — Large American cars from the early 1970s dominated the bottom of the fuel efficiency rankings.

6. **USA produced the most models** — 249 out of 398 vehicles (~62.6%) were of American origin, with Ford being one of the most represented brands.

---

## How to Run the Notebook

### Prerequisites

Make sure you have Python installed along with the required libraries:

```bash
pip install pandas seaborn matplotlib notebook
```

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/DS_201_Final-Project.git
   cd DS_201_Final-Project
   ```

2. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

3. **Open the notebook:**
   In the Jupyter browser interface, click on `Final_Project_Data_Exploration.ipynb`.

4. **Run all cells:**
   Go to **Kernel → Restart & Run All** to execute the entire notebook from top to bottom.

> No external data files are needed — the dataset loads automatically via `sns.load_dataset("mpg")`.
