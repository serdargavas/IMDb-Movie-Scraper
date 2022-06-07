# IMDB Movie Scraper

Scrape IMDb Movies with my code

## Description

Scraping using Python Scrapy with simple steps. Output format is JSON.

## Getting Started

### Dependencies

- Scrapy

### Installing

- Download zip file

### Executing program

- Install dependencies
- Create virtual enviroment
- Go into spiders folder in terminal

- To get all movies, write 'scrapy crawl movie -O movie.json'
- To get single movie, change the url in code and then write 'scrapy crawl movie_single -O movie-single.json'

### Output format

```
{"id": "tt1877830",
"type": "Movie",
"year": "2022",
"releaseDate": "2022-03-04",
"title": "The Batman",
"fullTitle": "The Batman (2022)",
"image": "https://m.media-amazon.com/images/M/MV5BZjlmYjY0MTEtYjNmOC00OWQ5LWEyMGEtYzYxYTc2MjI4MTVjXkEyXkFqcGdeQXVyMzMwOTU5MDk@._V1_QL75_UX380_CR0,0,380,562_.jpg", "plot": "When the Riddler, a sadistic serial killer, begins murdering key political figures in Gotham, Batman is forced to investigate the city's hidden corruption and question his family's involvement.",
"plot*short": "When the Riddler, a sadistic serial killer, begins murdering key political figures in Gotham, Batman is forced to investigate the city's hidden corruption and question his family's involvement.",
"runtimeStr": "2 hours 56 minutes", 
"runtimeMins": "176", 
"directors": ["Matt Reeves"],
"writers": ["Matt Reeves", "Peter Craig", "Bill Finger"], 
"stars": ["Robert Pattinson", "Zo\u00eb Kravitz", "Jeffrey Wright"], 
"companies": ["Warner Bros.", "6th & Idaho Productions", "DC Comics"], 
"countries": ["United States"], 
"genres": ["Action", "Crime", "Drama", "Mystery"], 
"imDbRating": 8.4, 
"metacriticRating": 72, 
"tagline": "Unmask The Truth", 
"actors": [{"image": "https://m.media-amazon.com/images/M/MV5BNzk0MDQ5OTUxMV5BMl5BanBnXkFtZTcwMDM5ODk5Mg@@._V1_QL75_UX280_CR0,0,280,280*.jpg", "name": "Robert Pattinson", "asCharacter": "as Bruce Wayne"}, {"image": "https://m.media-amazon.com/images/M/MV5BM2NmMWViOTYtOGJhYi00MzU2LWI5ODYtOGJhYzhkMWViODY5XkEyXkFqcGdeQXVyNjk2NTA3MTc@._V1_QL75_UX280_CR0,13,280,280_.jpg", "name": "Zo\u00eb Kravitz", "asCharacter": "as Selina Kyle"}, {"image": "https://m.media-amazon.com/images/M/MV5BMjI1NDYyNzk4OV5BMl5BanBnXkFtZTgwNDAyMzI1MDI@._V1_QL75_UY280_CR35,0,280,280_.jpg", "name": "Jeffrey Wright", "asCharacter": "as Lt. James Gordon"}, {"image": "https://m.media-amazon.com/images/M/MV5BMTg4NzM5NDk0MV5BMl5BanBnXkFtZTcwNzAzMTUxNw@@._V1_QL75_UX280_CR0,8,280,280_.jpg", "name": "Colin Farrell", "asCharacter": "as Oz"}, {"image": "https://m.media-amazon.com/images/M/MV5BMjMwMzE1OTc0OF5BMl5BanBnXkFtZTcwMDU2NTg0Nw@@._V1_QL75_UX280_CR0,4,280,280_.jpg", "name": "Paul Dano", "asCharacter": "as The Riddler"}, {"image": "https://m.media-amazon.com/images/M/MV5BNzYwNjgwMjMxMF5BMl5BanBnXkFtZTcwNjUwOTc3NQ@@._V1_QL75_UX280_CR0,0,280,280_.jpg", "name": "John Turturro", "asCharacter": "as Carmine Falcone"}, {"image": "https://m.media-amazon.com/images/M/MV5BYTgwYmM0ZjgtMWRmZC00YTc1LWIwYWEtYTFjMTZiMDNjNWRkXkEyXkFqcGdeQXVyNjcwMjczMzE@._V1_QL75_UX280_CR0,12,280,280_.jpg", "name": "Andy Serkis", "asCharacter": "as Alfred"}, {"image": "https://m.media-amazon.com/images/M/MV5BMjE0Mjg0NzE2Nl5BMl5BanBnXkFtZTcwMDE1MTkxMw@@._V1_QL75_UX280_CR0,0,280,280_.jpg", "name": "Peter Sarsgaard", "asCharacter": "as District Attorney Gil Colson"}, {"image": "https://m.media-amazon.com/images/M/MV5BMTcyNzEzMjY4NV5BMl5BanBnXkFtZTgwOTMzOTA5MjI@._V1_QL75_UX280_CR0,12,280,280_.jpg", "name": "Barry Keoghan", "asCharacter": "as Unseen Arkham Prisoner"}, {"image": "https://m.media-amazon.com/images/M/MV5BZTgwYzdjZWItZTdjYy00ODE2LTk1MWUtMTRjZWU5MTNkMjIyXkEyXkFqcGdeQXVyNjkwNzEwMzY@._V1_QL75_UX280_CR0,12,280,280_.jpg", "name": "Jayme Lawson", "asCharacter": "as Bella Re\u00e1l"}, {"image": "https://m.media-amazon.com/images/M/MV5BNWIyM2U4YzQtNjZiMS00ZmNjLTgyY2EtYjdjZmNlNmU3Y2U3XkEyXkFqcGdeQXVyNTQ0NDUzNjQ@._V1_QL75_UY280_CR1,0,280,280_.jpg", "name": "Gil Perez-Abraham", "asCharacter": "as Officer Martinez"}, {"image": "https://m.media-amazon.com/images/M/MV5BMTUyOTMxNzg3M15BMl5BanBnXkFtZTgwNjc3MDI3MTE@._V1_QL75_UX280_CR0,0,280,280_.jpg", "name": "Peter McDonald", "asCharacter": "as Kenzie"}, {"image": "https://m.media-amazon.com/images/M/MV5BNjM3OTc1Nzk0OF5BMl5BanBnXkFtZTcwOTEwNDA5Nw@@._V1_QL75_UX280_CR0,10,280,280_.jpg", "name": "Con O'Neill", "asCharacter": "as Chief Mackenzie Bock"}, {"image": "https://m.media-amazon.com/images/M/MV5BMDI5MmRmODEtNjIxZS00NWQxLWJkN2UtZDRjNjZkMzMyOWIyXkEyXkFqcGdeQXVyNDgzOTM5Nzc@._V1_QL75_UY280_CR33,0,280,280_.jpg", "name": "Alex Ferns", "asCharacter": "as Commissioner Pete Savage"}, {"image": "https://m.media-amazon.com/images/M/MV5BMjE1ODc2MjEzMV5BMl5BanBnXkFtZTgwNDg1MzQxMDE@._V1_QL75_UX280_CR0,10,280,280_.jpg", "name": "Rupert Penry-Jones", "asCharacter": "as Mayor Don Mitchell, Jr"}, {"image": "https://m.media-amazon.com/images/M/MV5BMTZkY2JmNzYtNDJmZS00N2FhLTg5MDItYjY3MTFlOTFiNDRlXkEyXkFqcGdeQXVyMTMwMzk2Mg@@._V1_QL75_UX280_CR0,0,280,280_.jpg", "name": "Kosha Engler", "asCharacter": "as Mrs. Mitchell"}, {"name": "Archie Barnes", "asCharacter": "as Mitchell's Son"}, {"image": "https://m.media-amazon.com/images/M/MV5BNjdkZWI2NjEtNjI1YS00NDFkLTk1ZGEtMjE0NmM1MjJkMDcwXkEyXkFqcGdeQXVyNTIyNTU1NDc@._V1_QL75_UX280_CR0,8,280,280_.jpg", "name": "Janine Harouni", "asCharacter": "as Carla"}], 
"keywordList": ["superhero", "based on comic", "dc comics", "batman character", "penguin character"], 
"languages": ["English"], 
"boxOffice": {"budget": null, "openingWeekendUSA": "$134,008,624", "grossUSA": "$300,014,069", "cumulativeWorldwideGross": "$600,414,069"}, 
"similars": [{"id": "tt0468569"}, {"id": "tt0372784"}, {"id": "tt1345836"}, {"id": "tt7286456"}, {"id": "tt10872600"}, {"id": "tt1464335"}, {"id": "tt0096895"}, {"id": "tt0103776"}, {"id": "tt2463208"}, {"id": "tt12593682"}, {"id": "tt9170236"}, {"id": "tt1160419"}], 
"images": [{"url": "https://m.media-amazon.com/images/M/MV5BMjU5ZTI4NjYtNjg5OC00NjQwLTk4M2QtMDJlZDNmMGQyZDY2XkEyXkFqcGdeQXVyMTkxNjUyNQ@@._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BYmI0MmNhNTYtOTg3Zi00YjM4LThiNDctYWZmYWM3ZjBiNDBmXkEyXkFqcGdeQXVyMTkxNjUyNQ@@._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BZmNkZTgwNTEtODhjOC00MmY3LTg3OWEtMDJjNzMwY2U1NWZiXkEyXkFqcGdeQXVyMTkxNjUyNQ@@._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BNTlhMmIxZWEtNzg5MC00M2U1LTk1YWQtMzVmOGE0ZGJkZDBjXkEyXkFqcGdeQXVyMTkxNjUyNQ@@._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BYjRhOWE0NmUtYjg4MS00OTk1LTg3N2ItOGMzZTgzMjA0ODMzXkEyXkFqcGdeQXVyMTMzNzIyNDc1._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BOGE2NWUwMDItMjA4Yi00N2Y3LWJjMzEtMDJjZTMzZTdlZGE5XkEyXkFqcGdeQXVyODk4OTc3MTY@._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BODRmZjcwNTYtNWQ1OC00YTgwLThlZmItZTQwZWE5ZWExNzlhXkEyXkFqcGdeQXVyMTA2ODkwNzM5._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BYjVmMGU3ZjAtMDNmMy00ZmE2LWI0ODQtMzc2NDczOTdlZjYyXkEyXkFqcGdeQXVyODk4OTc3MTY@._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BYzMwZjBiMjctZjYzZC00YTk0LWI2ZTAtNTgwNWZhYzhjOTA5XkEyXkFqcGdeQXVyODk4OTc3MTY@._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BMGZkZGFhMzEtYTZiNi00NTVlLTgyYjUtOTIyNjQ4NDE2ZWY0XkEyXkFqcGdeQXVyMTM1MTE1NDMx._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BZjJlYTllZGYtN2Y0Zi00MDg5LWFlNTktM2ExN2ZjZjc3ZGIxXkEyXkFqcGdeQXVyMTEyMjM2NDc2._V1_FMjpg_UX1280_.jpg"}, {"url": "https://m.media-amazon.com/images/M/MV5BYTExZTdhY2ItNGQ1YS00NjJlLWIxMjYtZTI1MzNlMzY0OTk4XkEyXkFqcGdeQXVyMTEyMjM2NDc2._V1_FMjpg_UX1280_.jpg"}], "video": "https://www.imdb.com/video/imdb/vi745521945/imdb/embed"}, 
```

## Help

You can message me for any issues. Keep that in mind imdb changin their structures too often that makes my code not work at all. Some of fields may require updates.

## Authors

@serdargavas
