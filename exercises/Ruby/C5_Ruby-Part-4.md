# Ruby Exercises - Part 4

## READ BEFORE STARTING

**Use Git or GitHub Desktop to commit each exercise  to GitHub** <br>

**Use a cloud based service or an IDE**<br>

**You can use one project for all exercises**<br>

- topics covered
  - bcrypt

**4.1 login + cli**
1. Create a CLI that allows the user to sign up and login. Use Bcypt to salt/hash the user passwords.
   Use class Notes as a resource.

- create a file called main.rb and include the following

```ruby
require 'bundler/inline'
gemfile do
    source 'http://rubygems.org'
    gem 'bcrypt'
end
require 'bcrypt'
```
- Bundler has an inline gemfile definition feature that lets you define gem dependencies in a single-file Ruby script. To use this feature, require 'bundler/inline' and provide a gemfile block that has the code that you normally put in a Gemfile.

2. Create your CLI in this file. 

