
# Netflix Data Cleaning Summary

## Dataset Used
- Netflix Movies and TV Shows dataset from Kaggle

## Cleaning Steps Performed
- Filled missing values in 'director', 'cast', and 'country' with 'Unknown'
- Dropped rows with missing 'date_added'
- Removed duplicate rows
- Standardized text data in 'type' and 'rating' columns to lowercase
- Converted 'date_added' to datetime format
- Renamed columns to follow snake_case convention

## Output
- Cleaned dataset saved as `cleaned_netflix_titles.csv`
