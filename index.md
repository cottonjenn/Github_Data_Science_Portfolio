---
title: "Welcome to My Data Science Portfolio"
---

# Hello! I'm Jenna 

Welcome to my data science portfolio! 

I'm a Statistics and Data Science major at BYU from Houston, Texas.
This site shows my journey learning data science and analytics. Here you'll find projects that demonstrate what I've learned and discovered.

Check out the [About Me tab](about.md) to know more about me and my background. 

## My Projects

::: {.grid}

::: {.g-col-lg-6 .g-col-12}
### [Golf Analytics Research](projects/golf.md)
In this project, I’m developing a spatial model that predicts—with uncertainty—how many strokes a professional golfer needs to hole out from any location on the hole, using 1,764 real shots from 139 players on Hole 1 of the 2023 Players Championship at TPC Sawgrass.
The raw shot coordinates came in an undocumented coordinate system, so I reverse-engineered the correct transformation using ArcGIS, built the full hole map from official shapefiles, and spatially joined every shot to precise boundaries (fairway, rough, bunkers, trees, green, fringe). I then fit both linear mixed-effects models (with player random intercepts) and an anisotropic 2D Matérn Gaussian process (Vecchia approximation in R’s gpgp package) to produce smooth, interpretable heatmaps of expected strokes remaining across the entire hole. This work demonstrates tough spatial data wrangling, coordinate system transformations, advanced mixed-effects and Gaussian process modeling, and turning complex geospatial data into actionable, visual insights. If you need someone who can clean, map, and model real-world location data end-to-end, this is a strong example.
:::

::: {.g-col-lg-6 .g-col-12}
### [NFL Big Data Bowl 2025 Prediction Competition](projects/nfl.md)
Using machine learning techniques in Python, I developed predictive models to forecast post release player movement based on player tracking data from the NFL Big Data Bowl 2025 competition. Coming soon!
:::

::: {.g-col-lg-6 .g-col-12}
### [NBA Scouting Report: Data Collection Project](projects/data-acquisition.md)
I created a data-driven scouting report that pinpoints international prospects who specifically fix the Sacramento Kings’ biggest weaknesses after a 17-year playoff drought. Starting from mock data, I leveled it up by web-scraping real 2020-21 NBA stats from Basketball-Reference using Python, Selenium, and BeautifulSoup, defeating JavaScript lazy-loading that static methods couldn’t handle. I cleaned and merged the data, engineered advanced metrics, and built a weighted “Kings Fit Score” focused on rebounding, playmaking, defensive impact, and efficiency.
The result: a ranked list of hidden-gem prospects who outperform the current roster exactly where Sacramento needs it most. This project showcases end-to-end web scraping, robust data cleaning, domain-driven algorithm design, clear visualization, and ethical data practices. If you’re looking for someone who can independently turn messy, real-world data into actionable insights—especially in sports analytics or high-impact decision support—this is a great example of how I work.
:::

::: {.g-col-lg-6 .g-col-12}
### [Tutorial Blog](blog.md)
Tutorial Blog made in markdown explaining a simple SQL topic for Data Science
:::

::: {.g-col-lg-6 .g-col-12}
### [Final Project: Baseball Performance vs Salary](projects/final-project.qmd)
Coming soon! Project in my Data Science class (BYU Stat 386) coded in Python and markdown. I explored the relationship between MBA performance and salary scraped from baseball-reference.com. I made a python package to data clean, visualize, and analyze regression to find insights. I presented my findings in a report and Stream-lit app.
:::

::: {.g-col-lg-6 .g-col-12}
### [Data Exploration Project](projects/eda.qmd)
Learn how I explore datasets to find interesting patterns and answer questions. Coming soon!
:::

:::
---

I built this site using [Quarto](https://quarto.org/) and host it on [GitHub Pages](https://pages.github.com/).

*Thanks for visiting! Feel free to explore my projects and see what I'm learning.*