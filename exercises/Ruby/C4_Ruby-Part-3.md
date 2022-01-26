# Ruby Exercises - Part 3

## READ BEFORE STARTING

**Use Git or GitHub Desktop to push this exercise to GitHub** <br>

**Use a cloud based service or an IDE**<br>

**You can use one project for all exercises**<br>

**Exercise 3.1: Classes**

1. Create a file called animal.rb
2. Define a called called Animal and give it attributes name, animal_type and color.
3. Initialize an Animal instance and store it in a variable called dog.
4. Access attributes name in dog and set it to "Clifford". Fill in the rest of the attributes.
5. Create an instance method called intro. When you call intro, it should print `Hey, my name is Clifford. I'm red and I am a dog` to the console. Use string interpolation and attributes to do this.
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

- `1`

```The Godfather
1. Rate the movie.
2. See your rating
3. Go back to main menu
```

- `1`
- `Please rate the movie from 1 - 5`
- `4`
- `Awesome!`

```Here's a list of my favorite movies!
Choose a movie
1. The Godfather
2. The Thing
3. Grown Ups
```
