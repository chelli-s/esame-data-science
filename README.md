Description:

This project analyzes the Top 5000 Albums of All Time dataset (source: Kaggle) using RStudio.

The analysis focuses on identifying trends in the global music industry through descriptive statistics, data visualization, and feature exploration of albums based on Spotify data.

Objectives:

Identify the most frequently occurring artists in the ranking.

Examine which time periods produced the most albums.

Compare and visualize genres.

Investigate specific features (danceability, energy, acousticness, duration) of the most represented artist, Miles Davis.

Analyze audience ratings over time.

Tools & Libraries

RStudio

R libraries:

tidyverse, dplyr, ggplot2 → data cleaning and visualization

plotly, gganimate, animation, gridExtra → interactive and animated plots

stringr → text processing

wordcloud2 → keyword visualization

Analysis Overview

Artists frequency: top artists with the highest number of albums in the dataset.

Timeline analysis: distribution of albums across decades.

Genre analysis: most represented genres and their relative frequencies.

Song duration: how average track length evolved across time.

Audience ratings: distribution and trends of ratings across decades.

Case study – Miles Davis: in-depth analysis of his genres, danceability, acousticness, and energy.

Project Structure

Top5000.csv → dataset used in the analysis

presentation.Rmd → main R Markdown file generating the ioslides presentation

style.css → optional custom CSS for presentation styling

plots/ → saved charts and visualizations

How to Run

Clone this repository.

Open the R Markdown file (.Rmd) in RStudio.

Install the required R libraries:

install.packages(c("tidyverse", "dplyr", "ggplot2", "plotly", "stringr", "wordcloud2", "gganimate", "animation", "gridExtra"))


Knit the file to generate the ioslides presentation.

Results & Conclusions

The most represented artists include Miles Davis, Bob Dylan, and The Beatles.

The 1965–1975 period was the peak of music production, with more than 600 albums ranked.

The most common genres are singer-songwriter and rock (with multiple subgenres).

Spotify audio features show meaningful insights about danceability, energy, and acousticness across decades and artists.
