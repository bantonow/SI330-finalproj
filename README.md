This notebook uses data from 3 sources to analyze trends in Uber ridership to recommend a good location for a new light rail Muni Metro line in San Francisco. It also looks at ridership data to detect trends over time.

Slides for the analysis can be found here: https://docs.google.com/presentation/d/11XPBE6LyX-pPNrg_TukRZRisuUZSDwSaeecXKwZjia8/edit?usp=sharing 

Thank you to Kaggle user @adyg1234 for inspiring these visualizations! Their work can be found here:
  https://www.kaggle.com/code/adyg1234/sf-uber-mobility-data-analysis/notebook
  https://www.kaggle.com/code/adyg1234/sf-muni-route-stops-visualization-basic-version/notebook

Datasets:
  1. San Francisco Uber Mobility Data: Geospatial data that logs when Uber rides pass through certain areas in the city (31.3 MB, 4 cols, 60k rows)
     https://www.kaggle.com/datasets/adyg1234/san-francisco-uber-mobility-data-q1-2020/data
     
  2. SFMTA Muni Route Data: Geospatial data that provides the paths of all the transit options in the city (434 kB, 11 cols, 130 rows)
     https://data.sfgov.org/Transportation/Muni-Simple-Routes/9exe-acju/about_data

  3. Muni ridership reports: Text/numerical data that catalogs monthly ridership for most routes in the transit system (155 KB, 4 cols, 1974 rows)
     https://www.sfmta.com/reports/muni-ridership-recovery-percentage-route-and-month
