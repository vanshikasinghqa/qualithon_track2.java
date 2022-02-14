# Qualitest - Qualithon'22 - Track 2 Challenge

## Challenge Objective
1. Fix failing test scripts if the failure is not a defect
2. Create new test cases 
3. Update tests code to execute tests on RottenTomatoes https://www.rottentomatoes.com/

## Test Cases
### Implemented Tests 
- MovieSearchTest#testSearchByExactMovieTitleReturnsMovieAsFirstResult : Verify that movie search with exact name returns result list with 1st result as the correct movie
- MovieSearchTest#testMovieMetadataOnWebHasCorrectDirectorName : Verify that movie page renders correct Director Name compared to the Movie metadata on OMDb http://www.omdbapi.com/ 
- MovieSearchTest#testMovieMetadataOnWebHasCorrectReleaseYear : Verify that movie page renders correct Release Year compared to the Movie metadata on OMDb http://www.omdbapi.com/
- MovieSearchTesttestMovieMetadataOnWebHasCorrectWriters : Verify that movie page renders correct list of Writers compared to the Movie metadata on OMDb http://www.omdbapi.com/
- MovieSearchTest#testMovieMetadataOnWebHasCorrectGenres : Verify that movie page renders correct list of Movie Genres compared to the Movie metadata on OMDb http://www.omdbapi.com/

### Pending Tests to be implemented
- MovieSearchTest#testMovieMetadataOnWebHasCorrectMaturityRating : Verify that movie page renders correct movie Maturity Rating compared to the Movie metadata on OMDb http://www.omdbapi.com/
- MovieSearchTest#testMovieMetadataOnWebHasCorrectMovieRatingScore : Verify that movie page renders correct IMDb Rating/Tomatometer Score compared to the Movie metadata on OMDb http://www.omdbapi.com/


### System Requirements to attempt challenge
 - Maven - 3.3.x
 - JDk   - 1.8+

### Run Tests:
```
  $> mvn clean test
```

