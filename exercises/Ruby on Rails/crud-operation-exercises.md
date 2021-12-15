# Ruby on Rails CRUD Opeation Exercises 

## READ BEFORE STARTING

**Use Git or GitHub Desktop to push each exercise to GitHub** <br>

**Use a cloud based service or an IDE**<br>

**You can use one project for all exercises**<br>

## Topics Covered 
**<em>Model</em>**
- created a model
- create migration files 
- test operations in the console 
- add validations
**<em>Controller</em>**
- created a controller 
- methods
- added routes
- instance variables
**<em>Views</em>**
- created views
- embedded ruby tags
**<em>Console</em>**
- testing ORM active record in rails consoles
- creating migration files
- scaffold commands
- generating models
**<em>Debugging</em>**
- byebug

Notes: [link](https://github.com/cruzgerman216/CodeLabs-Ruby-on-Rails-Class-Notes/blob/main/Class_8/BookIt_app_part_1.md)

**<em>Exercise 1</em>: Creating a schema file and a migration file**
1. Generate a rails application called migration-basics-rails-exercise
2. Generate a migration file called create_posts
3. In the migration file under the posts table, define attributes title of type string and description of type text. 
4. Run a command to the console to generate the schema file as well as update schema based on the new migration file created (NOTE: running the command will create the schema for the first time) 

**<em>Exercise 2</em>: Create/update schema, add attribute to table**
1. Generate a rails application called migration-basics-rails-part-2-exercise
2. Generate a migration file called create_animals
3. In the migration file under the animals table, define attributes name of type string and animal_type of type string
4. run a command to the console to generate the scema file as well as update the schema based on the new migration file created
5. Create another migration file that adds the attribute color of type string to the animals table.
6. Run the migration command again(if succesfful, you should see the attribute added onto the animal table in the schema file)

**<em>Exercise 3</em>: Manually creating a model**
1. Generate a raills application called basic-model-rails-exercise
2. Generate a migration file called create_users. In the file, add attributes name of type string and age of type number.
3. Use the migration command to create the schema file and to execute the migration file
4. Under models, create a user.rb file.
5. In user.rb, define the user class. This class inherits from ApplicationRecord
6. If successfull, run rails in the console and test out some executions such as ```User.all```, you should get nil or [] and not an error.

[Resource under section 5](https://guides.rubyonrails.org/active_record_basics.html)

**<em>Exercise 4</em>: ORM active record in rails console**
1. From exercise 3, go to the rails console and create three user records/instances.
   1. user 1 - name: "James", age: 32
   2. user 2 - name: "Johnny", age: 93
   3. user 3 - name: "Amy", age: 43
2. Use the new and save method to create another user
3. Get all users from the database
4. Get the user with id of 2
5. Get the user with the id of 1
6. Get the user with name Johnny
7. Get the user with age 35
8. Update user with name "James" to "Jim"
9. Update user with name "Amy" to "Sara"
10. Delete user with id 1
11. Delete all users from the Users table

**<em>Exercise 5</em>: Adding validations to User model**
1. From exercise 3, under the user model file, make name and age required
2. Make sure name is at least 2 characters and 50 characters long.
3. In the rails console, try creating a user without a name. You should get an error.
4. in the rails console, try to create a user with the name that is 1 character. You should get an error.

**<em>Exercise 6</em>: Creating a controller and view**

1. Generate a rails application called controller-view-rails-exercise
2. Manually create a pages controller
3. Define methods home and contact
4. Define the routes. Make the root path point to the home method defined in the pages controller
5. Create a pages folder under views
6. In pages, create a file called home.html.erb and create a couple of html elements in the file
7. Also, create another file called contact.html.erb and create a couple of html elements in the file
8. Run ```rails s``` to check for errors

**<em>Exercise 7</em>: MVC**
1. Manually create a migration file called manual-mvc-rails-exercise
2. Create a migration file called create_posts
   1. In the migration file, define attributes title of type string and description of type text. Run the migration command to create the schema file(running this command will also update it from the migration file)
3. Create a model file called post.rb under the models directory
   1. Define a class Post that inherits from ApplicationRecord cl
   2. Add validators that require title and description
   3. In the rails console, create a few posts.
4. Create a posts_controller file under the controller directory
   1. Define a class called PostsController and inherit from ApplicationController 
   2. Define a method called show that gets the parameter id. With the parameter id, find the user with the exact same id. Store the fetch user in an instance variable.(remember an instance variable name has @ in front of it)
   3. Setup the route 'show/:id' to point to the posts controller show method
5. Under the views folder, create a file called show.html.erb
   1. In show.html.erb, use embedded tags to output attributes regarding the instance variable you created in the show method.



