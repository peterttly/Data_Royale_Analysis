# Data_Royale_Analysis

End-to-end analytical study that transforms Clash Royale battle data into player behavior insights, meta strategy trends, and business-oriented findings around retention, progression, and in-game engagement.

##  Repository Structure
```markdown  
Data_Royale_Analysis/
│
├── data/                          <-- Raw input files (NOT uploaded to GitHub)
│   ├── clashroyale_master.parquet
│   ├── clashroyale.xlsx
│   ├── CardMasterListSeason18_12082020.csv
│
├── notebooks/                     <-- Jupyter notebooks used in analysis
│   ├── Data_Royale_Final_Python_Analytics.ipynb
│   ├── trophy_analysis.ipynb
│   ├── deck_meta_analysis.ipynb
│   ├── elixir_contour_analysis.ipynb
│   └── data_cleaning.ipynb
│
├── html_exports/                  <-- Exported HTML versions for judges
│   └── Data Royale Final Python Analytics.html
│
├── scripts/                       <-- Python modules used throughout
│   ├── multiprocessing_loader.py
│   ├── deck_core_extractor.py
│   ├── card_lookup_generator.py
│   └── visualization_utils.py
│
├── visuals/                       <-- Generated charts for the final report
│   ├── trophy_distribution.png
│   ├── core_cards_frequency.png
│   ├── elixir_contour_map.png
│   
│
├── README.md
└── requirements.txt
```



##  Project Overview
This repository contains the complete workflow used to analyze millions of Clash Royale battle logs for the **Data Royale** competition. Using multiprocessing, feature extraction, contour mapping, and deck meta analysis, we converted raw telemetry into clear insights about how players engage, progress, and make strategic decisions in the game.

##  Key Deliverables
- **Trophy distribution modeling** to identify high-engagement player segments  
- **Meta deck core extraction** revealing the most common 4-card combinations  
- **Card lookup table integration** for elixir cost & synergy analysis  
- **Elixir contour heatmaps** showing card usage vs. elixir patterns  
- **Business insight modeling** around player psychology and retention  

##  How to Run

### 1. Install dependencies
```bash
pip install -r requirements.txt

