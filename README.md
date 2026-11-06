# Movie Trends Before, During, and After COVID-19

## Overview

This repository contains code for collecting, cleaning, and analyzing movie data from [The Movie Database (TMDB)](https://www.themoviedb.org/) API. The project investigates how movie ratings, genre representation, and revenue differ among popular movies released before, during, and after the COVID-19 pandemic.

My analysis focuses on movies released between 2017 and 2025 and compares trends across three periods: pre-COVID, during COVID, and post-COVID.

## Repository Structure

### `data/`

Contains the datasets I used in the analysis, stored as JSON files:
- **Raw data:** Data collected directly from the TMDB API.
- **Processed data:** Cleaned and formatted data used for analysis.

### `scripts/`

Contains the Python scripts I used to:
- Collect movie data by querying the TMDB API.
- Process and clean the collected data for analysis.

### `images/`

Contains plots and other images I generated or used throughout the project:
- Line plot showing movie revenue trends from 2017 to 2025.
- Bar plot comparing movie genre counts across the three time periods.
- Box plot comparing movie-level average ratings across the three time periods.
- TMDB logo, included to comply with TMDB's API terms of use

### Analysis

The Quarto (`data_analysis.qmd`) file contains the code cells I used to load, process, explore, and analyze the cleaned dataset. It also generates the visualizations included in the `images/` folder.
