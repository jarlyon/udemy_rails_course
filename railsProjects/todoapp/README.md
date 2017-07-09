# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


MVC - Models, View, Controllers

snake_case --> for file names
CamelCase --> for Class names

migrations --> something that impacts the database
DB --
naming conventions --> lower case and plural 
Models help you interact with your database
--model naming convention -- lower case and singular

Creating todos:

.new creates a new object but does not save it to the DB!!
.save saves the object to the db (and +1 to the id)
.create will impact DB right away as long as there are no errors!
.destroy = deletes an id

resources :todos --> gives all the CRUD routes for todos

For a new Todo: initiate a new instance variable

corresponding actions:
new - form to create a todo
submit button to create a new db entry - hits the DB or gives an error

What is flash --> more or less a hash (key, value pair)
-- I can add messages to flash and then display the contents of the message that are in flash
--Flash is temporary -- once run it goes away