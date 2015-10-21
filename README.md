<h1>RottenPotatoes-Rails-Intro</h1>
Link to production: [https://desolate-scrubland-9981.herokuapp.com/movies](https://desolate-scrubland-9981.herokuapp.com/movies)

== Autograder ==
```
Your submission was recorded at 2015-10-21 13:47:45 +0000 : submission is on time.
Score: 308/308

App
  should respond to simple request [0 points]

Table header
  should have link to sort by title [10 points]
  should have link to sort by release date [10 points]

Table
  should be sortable by title [20 points]
  should be sortable by release date [20 points]
  should highlight title header when sorted [20 points]
  should highlight release date header when sorted [20 points]

GET /movies
  should be successful
  should have #ratings_form form [5 points]
  should have #ratings_submit button [5 points]
  should have checkboxes [5 points]
  When I first visit the page
    should have all checkboxes checked  [8 points]
    should have movies visible [7 points]
  when selecting a movie rating
    should only display movies of that rating [20 points]
    should automatically check the selected rating in the response [25 points]
  when selecting a sort column
    should preserve the ratings filter [25 points]

GET /movies
  basic tests
    should be successful
    should have a form with id ratings_form
    should have #ratings_submit button
    should have checkboxes
    should have #movies
    should have #title_header
    should have #release_date_header
  when selecting a movie rating
    should remember the rating selected [20 points]
    should allow new ratings to be selected [15 points]
    should redirect to a RESTful route [15 points]
  when selecting a sort field
    should remember the sort order [20 points]
    should allow a new sort order to be selected [15 points]
    should redirect to a RESTful route [15 points]

Finished in 3.64 seconds (files took 6953 minutes 25 seconds to load)
29 examples, 0 failures
```
