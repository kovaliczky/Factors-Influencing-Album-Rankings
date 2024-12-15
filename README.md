# Factors Influencing Album Rankings in the 2020 Rolling Stone 500 List

## Author
Eva Kovaliczky

---

## Research Question
The research question guiding this analysis is: **What factors determine an album’s ranking in the 2020 Rolling Stone 500 list?**

Specifically, this study seeks to understand how various attributes of an album, including its release year, popularity, and the characteristics of the artist, contribute to its position on the list.

To explore this, two linear regression models are compared:

1. **Simple Model**: Focused on album-level characteristics.
2. **Complex Model**: Incorporates both album-level and artist-level features.

This comparison aims to determine whether including artist characteristics leads to a more accurate or insightful understanding of an album’s ranking on the Rolling Stone 500 list.

---

## Models

### Model 1 (Simple Model)
This model examines the relationship between an album’s rank in 2020 and several key attributes:
- Release year
- Peak Billboard position
- Spotify popularity

These variables capture quantifiable characteristics of the album itself, without considering details about the artist.

### Model 2 (Complex Model)
This model expands on the simple model by including additional variables that account for artist-specific characteristics:
- Artist’s gender
- Number of members in the artist’s group
- Average birth year of the artist

This approach explores whether demographic and group dynamics influence an album’s success and ranking.

---

## Database
The dataset used for this analysis is the **Rolling Stone Album Rankings**, a curated dataset featured in TidyTuesday. It compares Rolling Stone’s “500 Greatest Albums of All Time” rankings from 2003, 2012, and 2020.

### Key Features of the Dataset
- **Album-level features**: Billboard position, Spotify popularity, release year
- **Artist-level features**: Gender, group size, and average birth year

This comprehensive dataset provides a foundation for studying trends in musical preferences and attributes of celebrated albums and artists over time.

---

## University Project
This analysis was prepared as the final project for the course **"Complex Data Analysis Procedures – Data Analysis with the R Programming Language"** in the Psychology Master’s program at **Eötvös Loránd University (ELTE)**.

---

## Files
- **`Factors_Influencing_AlbumRankings.Rmd`**: The R script containing the data analysis and model comparisons.
- **`Factors_Influencing_AlbumRankings.html`**: The HTML version of the analysis report for easy review.

---
