# Rails Getting Started Walkthrough

(previous lessons on Rails: [Intro to Rails, MVC and HTTP](https://github.com/ga-wdi-pvd/http-mvc-intro-rails), [Rails CRUD](https://github.com/ga-wdi-pvd/rails_features_CRD), [Rails Index Show](https://github.com/ga-wdi-pvd/rails_features_CRD/blob/master/index_show.md))

We are breaking the [Rails Getting Started Guide](http://guides.rubyonrails.org/getting_started.html) into 3 sections so developers get a step-by-step walkthrough for the most up to date version of Rails. They will create a fully functioning blog, complete with validations, associations and exposure to many features which make Rails a joy to work with:

 1. Hello World - Intro to rails and build first Rails app (Section 1...3, also covered with [Intro to Rails lesson](https://github.com/ga-wdi-pvd/http-mvc-intro-rails))
 2. Starting a Blog with Rails (sections 3...5.7 of Rails Guide - Getting Started)
 3. Finishing up Blog with Rails, adding 2nd model and associations (Section 5.7...7)
 4. (Stretch) Dry up code with partials and deleting associations; add basic auth (sections 7...10)
 
## Learning Objectives (ALL)

#### Part 1 - Intro to Rails
 - Describe the role of a web framework such as Rails
 - Describe the components of an MVC application
 - Diagram & annotate the lifecycle of an HTTP request in Ruby on Rails
 - Explain how Ruby on Rails implements MVC
 - Create a Rails application that displays "Hello Rails!"
 - List the most common folders in a Rails application and describe their purpose
 - Describe how to read, understand and fix errors in a Rails application

#### Part 2 - starting a blog with Rails
 - Create a new Rails application with Postgres as the default.
 - Explain why you would or would not use sqlite3 (the Rails default)
 - Explore the Rake command (Rails command in Rails 5) to create, edit, update and seed DB
 - Create Rails models using Rails generators and following Rails conventions
 - Inspect and Manipulate Rails models using the Rails console
 - Describe the full life cycle of a request/response in Rails
 - Implement a working Model View Controller pattern in Rails
 - Create objects by using RESTful routes and the MVC pattern in Rails
 - Delete objects using RESTful routes in Rails

#### Part 3 - finishing blog, adding associations and partials
 - Implement CRUD with an associated model
 - Use application layout to structure rendered views
 - DRY up rails code by using partials in forms and 'new' action
 - Refactor and DRY up even more: use partials in the show/index action
 - Describe how you can secure your app with Rails, and implement these methods in your blog

## Framing

Why reinvent the wheel? Let's use the tried-and-true Rails Getting Started guide to get familiar with creating a Rails app, and realizing our full potential with Rails

By the end of this unit, you will have a fully functioning database-backed blog application, complete with articles and associated comments.

## Review

 - What Rails helper do we use to create a form that is model-backed?
 - What is strong params and why do we use it to create/update?
 - What is a partial? Why is it helpful?
 - What is the file naming convention for a partial?
 - How do we indicate that we are using a partial in a view?
 - Describe the role of a web framework such as Rails
 - Describe the components of an MVC application
 - Diagram & annotate the lifecycle of an HTTP request in Ruby on Rails
 - Explain how Ruby on Rails implements MVC
 - Create a Rails application that displays "Hello Rails!" 
 - Where do we place the javascript and css of our rails application?
 - How might we drop into a debugging console during view execution? During controller execution? What debugger comes default with Rails?
 - What command allows us to create a new rails app with postgres as our default database?
 - Explain why you would or would not use sqlite3 (the Rails default)
 - Explore the available Rake commands. Which commands allow us to create, seed and drop a database?
 - How do we write a migration that creates a table with attributes, from the command line?
 - Is it possible to write multiple migrations in one migration file? How do we add a column and remove a column in one migration file?
 - Inspect and Manipulate Rails models using the Rails console
 - Describe the full life cycle of a request/response in Rails
 - Describe how Rails implements the MVC pattern?
 - What does the 'resources' keyword do in the routes.rb file?
 - How do you setup a delete link and route?
 - How do you setup a form_for method so a models' association is created?
 - Where do you add common view elements so all your views can share them?
 - Describe methods available to you to secure your Rails app, and talk through implementing these methods
  - http_basic_auth, strong parameters, validations

## Homework
- [Scribble](https://github.com/ga-wdi-pvd/scribble)
- Finish any of the Getting Started guide that we did not get to

## Resources
- [Rails Guide - Getting Started](http://guides.rubyonrails.org/getting_started.html)
- [Rails Guide - Form Helpers](http://guides.rubyonrails.org/form_helpers.html#dealing-with-model-objects)
- [Rails Guide - AR Migrations](http://edgeguides.rubyonrails.org/active_record_migrations.html)
- [WDI DC Lesson - Rails New Create Destroy](https://github.com/ga-wdi-pvd/rails_features_CRD/blob/master/new_create_destroy.md)
