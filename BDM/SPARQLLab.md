# SPARQL Lab

Discussions can be held on the Discussion Forum on Vision. This can be found under the Tools navigation menu item.

## Task 1: Run Lecture Queries

Load the two datasets available from Vision and make sure that you understand the queries presented in the lecture. There are notes Vision for running an instance of Apache Jena with Fuseki.

When running the queries, try altering them to return different information.

### Syntax Highlighting in Atom Editor

You need to install two extensions in Atom. On the lab machines go to Edit -> Preferences. This will open the settings window. On the left hand side you will see Install. Click on this and then type 'rdf' into the search box. Click on the Install button for 'language-rdf' and 'language-sparql'.

The highlighting should start automatically based on the file extension. If it doesn't, then you can always set the highlighting in the bottom right of the screen. 

## Task 2: Movie Queries

Using the Linked Movie Database that you loaded in Task 1, answer the following questions.

1. Return the names of all directors of movies, returning each name only once
2. Write the same query using a property path
3. Find the 20 most recent films by date (`dcterms:date`) or initial release date (`movie:initial_release_date`). Return the name and date.
   - Hint: Property path using `|`
4. Find all films released in 2007. Return the name and date, with the films sorted by the title.
5. Return the names of actors in Ghostbusters
6. Find the films that having 35 or more actors
   - Hint: Use `GROUP BY` and `HAVING`
7. Return the names of actors in Ghostbusters. Each film should have a single row response with the actor names being comma separated.
   - Hint: Use `group_concat`

## Task 3: Querying DBpedia

[DBpedia](https://wiki.dbpedia.org/) is a dataset that has been derived from the information boxes on Wikipedia. It covers a wide range of topics and has developed an [ontology](http://downloads.dbpedia.org/2014/dbpedia_2014.owl.bz2) to model this data. The 2016-10 version contains 13 billion triples but the data is available through the DBpedia SPARQL endpoint (http://dbpedia.org/sparql).

Work through the exercise sheet available on Vision for querying DBpedia.
