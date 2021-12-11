# Ruby Exercises - Four Part Series

## READ BEFORE STARTING

**Use Git or GitHub Desktop to push this exercise to GitHub** <br>

**Use a cloud based service or an IDE**<br>

**You can use one project for all exercises**<br>

## Part 1

**Exercise 1.1: Print to the console**

- Use the keyword p to print out `p` to the console
- Use the keyword puts to print out `puts` to the console
- Use the key word print to print out `print` to the console
- Create a local variable called my_name and set it to your name. Print it to the console.
- Create a variable called beginning_sentence and set it to `"My name is "`. Create another variable called full_sentence and set it equal to the combination of both beginning_sentence and my_name. Use the + operator to do that. Print full_sentence and you should get `My name is German` in the console.

**Exercise 1.2: Define a method**

- Define a method called say_hello_to. When you call the method, you should be able to see `Hello, John Doe!` in the console.
- Add a parameter called name to the method you just created. Use the parameter to print out `Hello, ` follow by the parameter name. Call the method and add the my_name variable as an argument.
  - Result: `Hello, German!`

**Exercise 1.3: Define a method with multiple arguments**

- Define a method called names_of_my_pets. Add three parameters to the method: name_1, name_2, name_3.
- Create three variables that correspond to the parameters of your method. Set them to whatever value you like.
- When calling the method, be should to add your variables as arguments and you should get something along the lines of `I have 3 pets! Their names are Apollo, Athena and Loki!` in the console.

**Exercise 1.4: Use built in string methods**

- Create a variable named sentence and set it to `Hello John Doe!`. Use the build in sub method to replace `Hello` with `Hi`. Print out the result. You should get `Hi John Doe!` in the console.
- Create a variable called solution and set it to `Hi John Doe!`. Use the built in match? method to check your output from the previous problem (see example of match?). Print the result and you should get `true` in the console.

Example:

```ruby
name = "John"
puts name.match?("Amy")
# false
```

**Exercise 1.5: Use escaping to output single quotes in a string**
- Output ```'Single Quotes'``` to the console (hint: use backslashes)

**Exercise 1.6: Print out user input**
- Use ```gets.chomp```. To get the user input, then store it in a variable called user_input. Print onto the console "You typed: " follow by what the user entered. 

NOTE: You can comment out this code to prevent you from always having to get user input

- Define a method named multiply_by_two with one parameter. Get the user input and use the method you defined to multiply that number by 2. Print the result.
- Define a method named divide_by_two with one parameter. Take in a user input and store and divide that value by two using divided_by_two. Print the result.

If user entered 5, result should be 2.5.

## Part 2
- topics covered
  - methods
  - arrays/iterators


**Exercise 2.1: if/else Conditionals**
  1. Print out ```What is your name?```. Get user input and store data in a variable called name
  2. Use an if statement to see if the name entered by the user is "john". If so, print out ```I found you!```.
  3. Use an else statement to print out ```You're not who I'm looking for ``` follow by the name the user entered.
  4. Use the built in string method ```downcase``` to downcase all letters of the user input in case he enters ```JoHn```.
  5. Change the print statement to ```What is your first name?``` Store user input in a variable. Add another print statement to ```What is your last name?``` Store user input in a variable. Use the if statement to heck to see if the first name is ```john``` and last name is ```doe```. Use ```&&``` to do this.
  6. Add an elsif statement to check if the first name and last name equate to ```Amy Jeans```. If so, print ```Amy! Help me look for John Doe.```
**Exercise 2.2: Arrays and iterators**
  1. Create an array with numbers 1 through 10
  2. Print out the first element of the array, the last element and its length using built in array methods
  3. Use ```unshift``` to add a number to the front of the array. Use ```<<``` to push a number to the end of the array.
  4. Use an iterator to print out each element of the array.
  5. Use an the each method to multiply each element in the array by 2 and print it
  6. Use the select method to only return odd numbers

**Exercise 2.3: More built in array methods**
1. Print out the array of built in methods

To see the methods
Example ```puts [].methods```
- Google them 

1. Create an array with three strings that resemble names. 
2. Use three different built in array methods that haven't been covered in this exercise.

**Exercises 2.4: Hashes**
1. Set a variable called user to a hash with keys email and id. Store values for theys keys
2. Print the values with keys email and id by accessing the user hash.
3. Choose and use three built in hash methods onto this object.

To see the methods
```puts {}.methods```

## Part 3
- topics covered
  - objects
  - classes


**Exercise 3.1: Classes**
1. Create a file called animal.rb
2. Define a called called Animal and give it attributes name, animal_type and color.
3. Initialize an Animal instance and store it in a variable called dog.
4. Access attributes name in dog and set it to "Clifford". Fill in the rest of the attributes.
5. Create an instance method called intro. When you call intro, it should print ```Hey, my name is Clifford. I'm red and I am a dog``` to the console. Use string interpolation and attributes to do this.
6. Create an initialize method for the Animal class that access three arguements name, animal_type and color. Use programming logic to set your attribute accessors.

**Exercise 3.2 Movie CLI**
1. Create a movie CLI gem that allows you to rate a movie and see the movie rating. 

Here's an example of what it may look like.
Here's the menu
```Here's a list of my favorite movies!
Choose a movie
1. The Godfather
2. The Thing
3. Grown Ups
```
When the user chooses a movie 
```1```

```The Godfather
1. Rate the movie.
2. See your rating
3. Go back to main menu
```
```1```
```Please rate the movie from 1 - 5```
```4```
```Awesome!```
```Here's a list of my favorite movies!
Choose a movie
1. The Godfather
2. The Thing
3. Grown Ups
```

