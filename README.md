# IMDB-Dashboard
A dashboard using the data also used in my R IMDB repo. Data was cleaned and organised in R ready for uploading to PowerBI. Data model was then created in PowerBI to display the data in a range of ways with the intent of providing an exploratory tool for the datasets. Info button provides a brief overview and lightbulb button provides some thoughts about the pages, the most relevant calculations and any improvements  (both buttons located top right).

Flaws: Genre and Director columns are partially incorrect as the original fields sometimes listed several entries in a single column. For this data the first entry was taken and others were removed due to hardware computing restraints. The genre field is particularly impacted by this as some genres are not as populated as expected and some films appear in genres that they might not be closely identified with.

The gross income data (downloaded from: ) doesnt match up with all of the movie titles but this was a quick fix as this dataset was a late addition in the development. If I had more time I would either attempt to clean the data to matchup more consistently with the IMDB dataset or find a different source.
