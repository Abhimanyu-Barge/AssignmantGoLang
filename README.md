# AssignmantGoLang 
I am using Echo High performance, extensible, minimalist Go web framework and mongdb as a database 
clone my repo and install depandancy 
enjoy!!!!!!!!

# Assignment task 

 1) Find movie by title by exact value that’s passed in the API. Notes: If there is no match in local
 database, use imdb-api package for the search. If that returns result(s), then store the result in
 database and return first value.
 #
method type :- post

url :- http://localhost:8081/search

payload: 
 {
	"SearchBy":"title",
	"SearchData":"Back to the Future"
 }

#
2)Search by Id

method type :- post

url :- http://localhost:8081/search

payload: 
{
	"SearchBy":"imdbid",
	"SearchData":"tt2884018"
}
#
 3)Search movies released in a particular year

method type :- post

url :- http://localhost:8081/search

payload: 
{
	"SearchBy":"year",
	"SearchData":"1985"
}

#
 4)Search movies with rating

method type :- post

url :- http://localhost:8081/search

payload: 
{
	"SearchBy":"imdbrating",
	"SearchData":"8.5"
 }

#
 5)Search movies with passed in genres value

method type :- post

url :- http://localhost:8081/search

payload:
{
	"SearchBy":"genre",
	"SearchData":"Adventure, Comedy, Sci-Fi"
 }

