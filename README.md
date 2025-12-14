# Netflix Analysis: Data-Driven Personalized Watchlist

## Overview

This project contains a comprehensive data analysis of Netflix movies and TV shows, focusing on IMDB ratings and viewer engagement. Through statistical analysis and data visualization, I've created a personalized watchlist of the best content available on Netflix.

## Analysis Summary

The analysis examined Netflix content based on:
- **IMDB Scores**: Critical acclaim and quality ratings
- **IMDB Votes**: Community engagement and popularity
- **Runtime**: Duration of content
- **Content Type**: Movies vs. TV Shows

### Key Findings

- A **statistically significant positive relationship** (p-value: 1.50e-10) exists between the number of votes and IMDB score, confirming that more engaged audiences tend to rate content higher.
- Out of the original dataset, **282 highly-rated titles** (IMDB ≥ 6.0 with ≥ 100,000 votes) were identified.
- From these, **36 exceptional titles** met the premium criteria of both high scores (> 8.5) AND high engagement (> 700,000 votes).

## Files in this Repository

- `Netflix.ipynb` - Jupyter notebook containing the complete analysis with visualizations and statistical insights
- `README.md` - This file

## My Personalized Netflix Watchlist (36 Titles)

Based on the analysis, here are the 36 titles I've selected to watch on Netflix:

1. Breaking Bad
2. Avatar: The Last Airbender
3. The Last Dance
4. Arcane
5. Attack on Titan
6. DEATH NOTE
7. Cowboy Bebop
8. Seinfeld
9. When They See Us
10. Peaky Blinders
11. Forrest Gump
12. Black Mirror
13. BoJack Horseman
14. One Piece
15. Better Call Saul
16. Narcos
17. Inception
18. The Crown
19. Stranger Things
20. Arrested Development
21. One-Punch Man
22. Downton Abbey
23. Dark
24. House of Cards
25. Mindhunter
26. Cobra Kai
27. Saving Private Ryan
28. Shameless
29. The Queen's Gambit
30. The Haunting of Hill House
31. Django Unchained
32. Taxi Driver
33. Full Metal Jacket
34. The Walking Dead
35. How to Train Your Dragon
36. The Imitation Game

## Data Visualization & Analysis

The notebook includes:
- **Scatter plots** showing relationships between IMDB scores, runtime, and votes
- **Regression analysis** with trend lines and R² values
- **Statistical significance testing** (p-values)
- **Aesthetic data tables** displaying the top-rated content
- **Detailed statistics** on dataset composition and filtering

## Methodology

1. **Data Filtering**: Filtered Netflix dataset to include only content with IMDB scores ≥ 6.0 and at least 100,000 votes
2. **Statistical Analysis**: Used linear regression to analyze correlations between variables
3. **Premium Selection**: Selected titles with IMDB score > 8.5 OR votes > 700,000
4. **Sorting**: Ranked by IMDB score (descending) for quality-first approach

## Conclusion

This data-driven approach ensures that my Netflix viewing time is spent on content that is both critically appreciated and widely enjoyed by the community. Each of the 36 titles has demonstrated exceptional quality (high IMDB scores) and significant popularity (high engagement), making them reliable choices for an excellent viewing experience.

## Technologies Used

- Python
- Pandas (Data manipulation)
- NumPy (Numerical analysis)
- Matplotlib & Seaborn (Static visualizations)
- Plotly (Interactive visualizations)
- SciPy (Statistical analysis)

---

**Created**: December 2025
**Author**: Hemanth V
