# Ruby Exercises - Part 3

## READ BEFORE STARTING

**Use Git or GitHub Desktop to commit each exercise to GitHub** <br>

**Use a cloud based service or an IDE**<br>

**You can use one project for all exercises**<br>

**Exercise 3.0: Terminology** 
Copy and paste the contents of Part 2 in your README.md file.
``` 
.
.
.

## Part 3
<em>**What is Object Oriented Programming?**</em> - INSERT DEFINITION HERE <br>
<em>**Class inheritance**</em> - INSERT DEfINNITION HERE <br>
<em>**What are getters and setters?**</em> - INSERT ANSWER HERE <br>
<em>**Difference between class variables and instance variables and class attributes?**</em> - INSERT ANSWER HERE <br>
<em>**What does self signify in a class?**</em> - INSERT ANSWER HERE <br>
<em>**Modules</em> - INSERT DEfINNITION HERE <br>

## Part 4
```

- replace each <em>INSERT DEFINITION/ANSWER HERE</em> with the correct definition/answer in your own words. Using external resources are recommended.<br>

**Exercise 3.1: Basic class**
Create a Ruby file called exercise-3.1.rb. 

1. Define a class called `box`
2. Create three new `box` instances.


**Exercise 3.2: Animal class**
Create a Ruby file called exercise-3.2.rb. 

1. Define a class called `Animal` and set attributes `name`, `animal_type` and `color` using the method attr_accessors (keep in mind, attributes refer to instance variables).
2. Initialize an Animal instance and store it in a variable called dog.
3. Access attributes `name` in dog and set it to "Clifford". Fill in the rest of the attributes.
4. Print out each attribute dog holds.

Output 
```
> My name is Clifford. 
> I am a dog.
> My fur color is red.
```

4. Create an instance method called `intro`. When you call `intro`, it should print `Hey, my name is Clifford. I'm red and I am a dog` to the console. Use string interpolation to do this.

**Exercise 3.3: Rectangle class**
Create a Ruby file called exercise-3.3.rb. 

1. Define a class called `Rectangle` with instance variables `length` and `width`.
2. Define an instance method called `area`. This method should return the multiplication of `length` and `width`.
3. Define an instance method called `parameter`. This should return the addition of all sides of the "rectangle" such as 
```
w + w + l + l
```
w refers to width 
l refers to length

**Exercise 3.4: Human class**
Create a Ruby file called exercise-3.4.rb. 

1. Define a class called `Person` and set instance attributes `name` and `age` using the method attr_accessors.
2. Define an initialize method that will set each attribute. 
3. Create a class variable called `people`.
4. Every time an instance gets created, push that instance in the class variable people. Do so in the initialize method.
5. Create a class method called `print_all_people`. Loop through people and print each name and age in the format of `"Name: John Doe, Age: 54"`. Call this method to see if the results are correct.

**Exercise 3.5: Class inheritance** 
Create a Ruby file called exercise-3.5.rb.

1. Define four class `Person`, `Doctor`, `Teacher` and `Engineer`. 
2. In the Person class, define an instance method called `eat` with a paramter called food. This method should print out "Eating " follow by food. 
3. In `Person`, create attributes `weight`, `height`, `name`. 
4. In `Person`, define an initialize method and set these attributes by passing in arguments upon instantiation.
5. Make `Doctor`, `Teacher`, and `Engineer`inherit from `Person`.
6. For each class except Person, upon instantiation, print out "I am a " follow by the type of profession this person is in. 
For example, "I am a Doctor!".
7. Create a doctor instance, teacher instance, and engineer instance and check if they contain these atrtributes and methods inherited from the parent class `Person`.

**Exercise 3.6: Modules**
Create a Ruby file called exercise-3.6.rb

1. Define a class called Person. 
2. Define a module called traits. In the module, define a method called eat and print out "Eating".
3. Include the module in the Person methods. Allow each person instance to call these methods the module gives.