# CRUDAPI_GoLang

# Go Movie API (CRUD)
A simple RESTful API built with Go and Gorilla Mux to manage movies.

## Features
Get all movies
Get a movie by ID
Create a movie
Update a movie
Delete a movie

## Tech
Go
Gorilla Mux
Postman (for testing)

## Run Locally
```bash
go mod init movieapi
go get github.com/gorilla/mux
go run main.go
Server runs at: http://localhost:8080



ROUTES	            FUNCTIONS 	   ENDPOINTS	    METHODS	   POSTMAN
Get All Movies 	    getMovies() 	 /movies	      GET	       localhost:8080/movies
Get Movies by ID   	getMovie()	   /movies/{id}	  GET	       localhost:8080/movies/1
Create Movie	      createMovie()  /movies	      POST	     localhost:8080/movies
Update Movie	      updateMovie()	 /movies{id}	  PUT	       localhost:8080/movies/1
Delete Movie	      deleteMovie()	 /movies/{id}	  DELETE	   localhost:8080/movies/1
