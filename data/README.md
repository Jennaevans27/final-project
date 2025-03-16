# data

Place data file(s) in this folder.

Then, include codebooks (variables, and their descriptions) for your data file(s)
using the following format.
uesdata <- tidytuesdayR::tt_load('2024-07-30')

summer_movie_genres <- tuesdata$summer_movie_genres
summer_movies <- tuesdata$summer_movies


## Summer Movies 

- `tconst`: alphanumeric unique identifier of the title
- `title_type`: the type/format of the title (movie, video, or tvMovie)
- `primary_title`: the more popular title / the title used by the filmmakers on promotional materials at the point of release
- `original_title`: original title, in the original language
- `year`: the release year of a title
- `runtime_minutes`: primary runtime of the title, in minutes
- `genres`: includes up to three genres associated with the title (comma-delimited)
- `simple_title`: the title in lowercase, with punctuation removed, for easier filtering and grouping
- `average_rating`: weighted average of all the individual user ratings on IMDb
- `num_votes`: number of votes the title has received on IMDb (titles with fewer than 10 votes were not included in this dataset)



