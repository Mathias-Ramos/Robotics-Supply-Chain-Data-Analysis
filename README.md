stock-analysis/
│
├── data/
│   ├── raw/
│   │   └── stocks.csv
│   │
│   └── processed/
│       └── stocks_clean.csv
│
├── src/
│   ├── ingestion/
│   │   └── load.py
│   │
│   ├── transformations/
│   │   ├── cleaning.py
│   │   └── feature_engineering.py
│   │
│   └── analysis/
│       ├── descriptive.py
│       └── visualization.py
│
├── notebooks/
│   ├── 01_data_quality.ipynb
│   ├── 02_eda.ipynb
│   └── 03_analysis.ipynb
│
├── research/
│   └── market_context.md
│
├── tests/
│   └── test_cleaning.py
│
└── README.md