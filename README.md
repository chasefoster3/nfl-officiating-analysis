# NFL Officiating Patterns: An Exploration of Team Trends, Officiating Crews, and Shifts After the Rise of Legal Sports Wagering

**Graduate Team Project**  
**Master of Information and Data Science**  
**University of California, Berkeley**

---

## Overview

This project explores how NFL officiating patterns have evolved over the 2015–2024 seasons, with a particular focus on changes occurring after the widespread legalization of sports betting in the United States. Using over 440,000 NFL plays, our team conducted an exploratory data analysis to investigate league-wide penalty trends, officiating crew tendencies, replay review outcomes, and team-specific officiating patterns.

While this analysis identifies several interesting trends, it is exploratory in nature and does not establish causal relationships between sports betting and officiating behavior.

---

## Research Questions

This project sought to answer the following questions:

- Have NFL penalty trends changed following the legalization of sports betting?
- Do officiating crews differ in how frequently they call penalties?
- Have replay review outcomes changed over time?
- Are certain teams consistently penalized more than others?
- How have league-wide officiating patterns evolved from 2015–2024?

---

## Dataset

### Source

- NFLverse play-by-play dataset (accessed through `nflreadpy`)
- NFL game-level data

### Seasons

- 2015–2024

### Dataset Size

- 440,000+ individual plays
- 2,700+ NFL games
- 26 cleaned variables used in the final analysis

---

## Methodology

The project followed a complete exploratory data analysis workflow.

### Data Collection

- Imported NFL play-by-play and game data using nflreadpy.
- Combined multiple seasons into a single dataset.

### Data Cleaning

- Removed unnecessary variables
- Addressed missing values
- Standardized variable names
- Created new features for analysis

### Exploratory Data Analysis

The analysis focused on several aspects of NFL officiating:

- Penalty frequency over time
- Penalty yardage trends
- Team penalty rates
- Referee penalty tendencies
- Replay review frequency
- Replay reversal rates
- Team × referee interactions

### Visualization

Created multiple visualizations to communicate findings, including:

- Line charts
- Bar charts
- Heatmaps
- Scatter plots
- Summary tables

---

## Key Findings

### League-Wide Trends

- Overall penalty frequency declined during the post-betting era.
- Average penalty yardage also decreased.
- Officiating became more consistent across referee crews over time.

### Replay Reviews

- Replay reviews became less frequent.
- Replay reversal rates increased in recent seasons.

### Team Trends

- Several teams consistently ranked among the most and least penalized.
- Penalty rates varied substantially across organizations.

### Officiating Crews

- Individual officiating crews demonstrated measurable differences in penalty tendencies.
- Variation between crews decreased over time, suggesting greater league-wide consistency.

---

## Technologies Used

### Programming

- Python

### Libraries

- pandas
- NumPy
- matplotlib
- Plotly
- nflreadpy

### Development Environment

- Jupyter Notebook

---

## Repository Structure

```
nfl-officiating-analysis/

│── README.md
│── LICENSE
│── .gitignore

├── data/
│   └── Data documentation

├── notebook/
│   └── Exploratory analysis notebook

├── figures/
│   └── Visualizations used throughout the project

├── report/
│   └── Final project report

└── presentation/
    └── Final presentation slides
```

---

## My Contributions

This project was completed as part of a graduate team in the UC Berkeley Master of Information and Data Science program.

My contributions included:

- Data cleaning and preprocessing
- Exploratory data analysis
- Statistical summaries
- Data visualization
- Interpretation of analytical findings
- Preparation of the final presentation and report

---

## Skills Demonstrated

- Exploratory Data Analysis (EDA)
- Data Cleaning
- Data Visualization
- Feature Engineering
- Statistical Analysis
- Python Programming
- Team Collaboration
- Data Storytelling
- Sports Analytics

---

## Future Work

Potential extensions of this project include:

- Statistical hypothesis testing of observed trends
- Causal inference methods to investigate potential effects of legalized sports betting
- Predictive modeling of penalties and replay decisions
- Team-adjusted officiating metrics
- Interactive dashboards for exploring officiating trends

---

## Acknowledgments

This project was completed as part of the Master of Information and Data Science program at the University of California, Berkeley.

Data were obtained from the NFLverse project using the `nflreadpy` package.

---

## Contact

If you have questions about this project or would like to discuss the analysis, feel free to connect with me on LinkedIn or reach out via email.
