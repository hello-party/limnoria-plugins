Queries OMDB database for information about IMDB titles

```
@load IMDB

@config plugins.imdb.template $title $year, $country - $imdbRating ¶ $plot ♥ http://imdb.com/title/$imdbID
```
