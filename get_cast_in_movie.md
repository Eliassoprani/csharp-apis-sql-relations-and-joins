SELECT m.title, people.name FROM movies m JOIN casts ON casts.movie_id = m.id JOIN actors ON casts.actors_id = actors.id JOIN people ON actors.people_id = people.id WHERE m.title='Star Wars: A New Hope';