movies.dat contains the list of movies from the largest Movielens Dataset
run 'aggregateMovieInfo.py'. It will fetch the details of the movies in movies.dat and place it in movieInfo.dat.
Now, movieInfo.dat has to be cleaned.
run 'formatTheRaw.py'. It will remove the hardcoded attributes from movieInfo.dat and writes it onto 'movielens_10m'
run 'createMovieSet.py'. It will read the movie list ('movies.dat' of 1m dataset) and reduce 'movielens_10m' to 'movielens_1m'

run 'generateUserData.py'. It will create a json file 'movielens_userData.json' that contains the list of users and the movies that they've watched.