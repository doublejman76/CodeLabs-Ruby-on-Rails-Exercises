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
