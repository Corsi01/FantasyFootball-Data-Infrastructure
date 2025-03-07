# Fantacalcio Data Infrastructure

## Overview
This project builds a structured data infrastructure to support fantasy football (**Fantacalcio**) players in evaluating **Serie A** players before the season starts. It integrates data from multiple sources using **APIs and web scraping** to create a comprehensive **MongoDB** database.

The primary goal is to assist Fantacalcio participants during the **auction phase**, where they draft players based on historical performance and fantasy football-specific metrics.

## Features
- 📊 **Team Rosters**: Complete rosters of all Serie A teams at the start of the season.
- ⚽ **Player Statistics**: Data from the previous season, including goals, assists, and minutes played.
- 🎯 **Fantasy Ratings**: Historical Fantacalcio scores to assess player value.
- 🏗️ **Data Cleaning & Integration**: Merging API data with scraped data from **Transfermarkt** and **Fantacalcio.it**.
- 📂 **MongoDB Storage**: Organized collections for **teams, players, and matchday performances**.

## Data Sources
- **[Sports.io API](https://www.sports.io/)** – Used to fetch team rosters and player stats.
- **[Transfermarkt.it](https://www.transfermarkt.it/)** – Scraped for verifying player transfers.
- **[Fantacalcio.it](https://www.fantacalcio.it/)** – Scraped for fantasy football-specific ratings.

## Technologies Used
- **Python** 🐍 (Data Processing & Scraping)
- **Jupyter Notebook** 📓 (Development & Analysis)
- **MongoDB** 🍃 (Database Storage)
- **RapidFuzz** 🔍 (Fuzzy Matching for Data Integration)

## Database Structure
MongoDB is structured into **three main collections**:
1. **Teams** – Stores team rosters and player roles.
2. **Players** – Contains player details, performance stats, and transfers.
3. **Fantasy Data** – Captures matchday ratings for fantasy football evaluation.

## Challenges & Future Improvements
✅ **Current Challenges**:
- Handling inconsistencies between API and scraped data.
- Manual intervention required for name matching.
- Some missing data for lesser-known players.

🚀 **Future Enhancements**:
- Automate error correction using AI-based text matching.
- Extend support for additional leagues.
- Optimize web scraping for efficiency and reliability.

## License
MIT License © 2024 – Open-source contributions welcome!
