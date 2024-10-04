# Blog App

A simple blog application built with Ruby on Rails. This application allows users to create, read, update, and delete blog posts.

## Technologies Used

   ```bash
- Ruby: Programming language (version 3.2.2).
- Rails: Web application framework (version 7.1.3).
- SQLite3: Database used for development and testing.
   ```

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Gouravsen7/blog-app.git  # Clone the repository to your local machine
   cd blog-app                  # Navigate into the project directory
   ```

2. **Install dependencies**:

   ```bash
   gem install bundler          # Install the Bundler gem for managing gem dependencies
   bundle install               # Install all the gem dependencies specified in the Gemfile
   ```

3. **Set up the database by running the following commands**:

   ```bash
   rails db:create              # Create the database for development and test environments
   rails db:migrate             # Run migrations to set up the database schema
   ```

4. **To start server**:

   ```bash
   rails server                 # Start the Rails server, allowing you to access the app
   ```

5. **To run the test suite using RSpec, use**:

   ```bash
   bundle exec rspec            # Execute the test suite to run all RSpec tests
   ```

## API Documentation

- You can use the following Postman collection to test the API endpoints:

   - [Postman Collection](https://documenter.getpostman.com/view/37841321/2sAXxMeYLb)
