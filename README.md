# OTT Rating Analysis & Interactive Content Recommendation System

## Overview

This project is a simple Python command-line application built to help viewers quickly discover what to watch across OTT platforms. Using a dataset of 2,500 movies and web series, the program takes user preferences through numbered prompts, validates every input, filters matching titles by type, genre, and minimum rating, and displays the top trending recommendations with runtimes converted into hours and minutes.

## Student Details

* Name: Akshat Kumar Verma
* Roll No.: 2026B01010373
* Course: B.Tech, Computer Science and Engineering (1st Year)
* Subject: HCL Data Analysis
* Guide: Meenakshi

## Features

* Numbered menu prompts for Content Type (1-3) and Genre (1-8)
* Input validation loops that re-ask each question until valid input is entered
* Filters titles by minimum Rating (5.0 - 9.5), Type, and Genre
* Ranks matching results by Trending_score in descending order
* Converts runtime from minutes into hours and minutes (Xh Ym)

## Dataset

* File: ott_movies_clean_unique.csv
* Size: 2,500 records and 17 columns (no missing values)
* Covers Movies and Series (2015-2024) on Netflix, Prime Video, and Hotstar

## Requirements

* Python 3
* pandas (`pip install pandas`)

## How to Run

1. Place `ott_movies_clean_unique.csv` and `recommender.py` in the same folder.
2. Open a terminal in that folder and run:
   `python recommender.py`
3. Follow the numbered prompts on the screen to get your recommendations.
