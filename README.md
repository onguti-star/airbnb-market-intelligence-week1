# Airbnb Market Intelligence & Pricing Analysis (Track B - Data Science)

## Project Overview
This project investigates how physical property characteristics (room types, accommodation capacity, and number of bedrooms) influence advertised listing prices within major Airbnb city markets, using Paris as the primary analytical focus.

## Tools & Technologies
* **Environment:** VS Code & Jupyter Notebook (`.ipynb`)
* **Libraries:** Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy

## Project Directory Structure
```text
├── airbnb_analytics.ipynb        # Main reproducible Jupyter notebook
├── Listings_clean.csv            # Cleaned listings data the notebook reads from
├── Visualisations/               # Folder containing all 5 generated charts
│   ├── cities_room_types.png
│   ├── paris_roomtype_price.png
│   ├── paris_capacity_price.png
│   ├── paris_price_histogram.png
│   └── paris_correlation_heatmap.png
├── requirements.txt              # Python dependencies
└── README.md                     # Project documentation
```

## How to Reproduce This Analysis

### Prerequisites
- Python 3.x

### Setup
1. Clone this repository.
2. Install dependencies: `pip install -r requirements.txt`

### Running the analysis
Open `airbnb_analytics.ipynb` in Jupyter or VS Code and run all cells in order. The notebook reads directly from `Listings_clean.csv` included in this folder — no database connection or credentials are required.