# Ruby on Rails Exercises 

## READ BEFORE STARTING

**Use Git or GitHub Desktop to push this exercise to GitHub** <br>

**Use a cloud based service or an IDE**<br>

**You can use one project for all exercises**<br>

Notes: [link](https://github.com/cruzgerman216/CodeLabs-Ruby-on-Rails-Class-Notes/blob/main/Class_7_Intro_to_Ruby_on_Rails/ruby_on_rails_notes.md)

**<em>Exercise 1</em>: Creating a basic Rails app**
- Generate a rails application called my-first-rails-app
- Launch a web server that bundles the rails application
- Manually create a pages controller file
- Define a method called profile
- In the pofile method, render a string "My profile"
- Create a path that routes to 'myProfile' and setup the corresponding controller and method.
  **NOTE: when updating the route.rb file, you will have to restart your web server**
- push to GitHub

**<em>Exercise 2</em>: Creating an erb file**
- Generate a rails application called rails-exercise-2-app
- Manually create a movies controller file
- Define a method called movies_list
- Create an erb file called movies. In the file, create an h1 element with content ```List of Movies```
- In the movies_list method, render the movies erb file.
- Create a path that routes to 'movies-list' and set up the corresponding controller and method.
- run ```rails s```, you should be able to see ```List of Movies``` in 'localhost:3000/movies-list'
- push to GitHub

**<em>Exercise 3</em>: MVC application**
- Generate a rails application called rails-basic-mvc-app
- Use the scaffold command to generate Post which includes fields title which is of type string and description which is of type text.
- Because you generated a model, create a schema by migrating the files using ```rails db:migrate```
- run ```rails s``` and go through the application.
- push to GitHub

**<em>Exercise 4</em>: More rails**
- generate a rails application called rails-exercise-4-app
- Manually create or generate a controller called pages.
- Define methods home and about
- In the route.rb file, create a root path that is set to the home method in the pages controller.
- Create another route that is set to the about method in the pages controller
- Create an ERB for each home and about method
- Render both erb file to the corresponding methods that exist in the pages controller.