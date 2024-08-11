# Premier League Match Data Analysis

Welcome to the Premier League Match Data Analysis repository! This project provides a comprehensive analysis of Premier League match data, focusing on extracting and combining detailed statistics from multiple seasons.

## Project Overview

This repository contains scripts and data that aggregate and analyze Premier League match information from the 2021-2022 season onward. The primary objective is to offer insights into team performance and match statistics, including various metrics such as shooting accuracy, shot distance, and more.

## Data Collection

The data was scraped from the FBref website, which provides detailed statistics for Premier League matches. The process involved:

1. **Fetching Team and Match Data**: Data was collected for multiple seasons by scraping the standings and fixture pages for all teams.
2. **Extracting Shooting Statistics**: Additional shooting statistics were retrieved for each team to provide a deeper analysis of their performance.
3. **Merging Data**: Match data was merged with shooting statistics to create a comprehensive dataset for each team.

## Data Description

The dataset includes the following columns:

- `date`: Date of the match
- `time`: Time of the match
- `comp`: Competition (e.g., Premier League)
- `round`: Matchweek
- `day`: Day of the week
- `venue`: Home or Away
- `result`: Result of the match (Win/Loss/Draw)
- `gf`: Goals For
- `ga`: Goals Against
- `opponent`: Opposing team
- `sh`: Total Shots
- `sot`: Shots on Target
- `dist`: Average Shot Distance
- `fk`: Free Kicks
- `pk`: Penalties
- `pkatt`: Penalty Attempts
- `season`: Season of the match
- `team`: Team name

## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git


## Contribution
Feel free to contribute to this project by opening issues, submitting pull requests, or providing feedback. Your contributions are welcome!


