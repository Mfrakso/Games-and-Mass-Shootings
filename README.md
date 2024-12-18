# Games-and-Mass-Shootings
This analysis explores the relationship between shooting incidents and video game sales, particularly focusing on first-person shooter (FPS) games. The data spans from 1966 to 2016 and combines information from various sources, including shooting incidents, console game sales, and Steam game data. The final analysis is presented through visualizations and statistical analyses to understand trends and correlations.

Prerequisites


Shooting Data (dictionary_stanford_msa_release_06142016.csv): Data on various shooting incidents.
Console Game Data (vgsales.csv): Video game sales data for consoles, including the genre and sales in North America.
Steam Game Data (steam.csv): Information on Steam games, including the number of owners and genre tags.
Ensure the following R libraries are installed and loaded for the analysis:

dplyr: For data manipulation.
ggplot2: For data visualization.
lubridate: For working with dates.
stringr: For string manipulation.
reshape2: For reshaping data (e.g., splitting columns).
