# US Exports to the Dominican Republic 1992 2017
This project was developed as a beginner portfolio exercise to practice data cleaning, trend analysis, and data visualization using a real-world trade dataset.

## Project Overview
This project analyzes exports from U.S. states and territories to the Dominican Republic from 1992 to 2017. The goal is to identify which states contributed the most to total export value and to explore how concentrated this trade relationship was over time.

## Objective
To examine the evolution of U.S. exports to the Dominican Republic and determine whether export activity was concentrated in a small number of states.

## Dataset
The dataset contains annual export values in U.S. dollars by U.S. state and territory from 1992 to 2017.

Main fields used:
- Year
- Dollars
- Abbrev
- State

## Data Cleaning
- Removed the redundant technical field: `StateCode`
- Extracted `Year` from the original date field
- Corrected the missing state name for `VI` as `Virgin Islands`
- Kept `State` and `Abbrev` for readability and validation

## Key Questions
- Which states had the highest cumulative export value?
- How did total export value change over time?
- How much of total exports was explained by the top 5 states?
- Were there states with low or inconsistent participation?

## Tools Used
- Excel
- Power BI

## Project Status
This is a beginner-level exploratory data analysis practice project. The analysis and dashboard are currently in progress.
