# Yelp MVP

Project developed during the [Le Wagon](https://github.com/lewagon) BootCamp Full Stack.

## Objective

The objective of this challenge is to build a two-model Rails app with a restaurant and anonymous
reviews.

- A visitor can see the list of all restaurants.

  ```bash
    GET "restaurants"
  ```

- A visitor can add a new restaurant, and be redirected to the `show` view of that new restaurant.

  ```bash
    GET "restaurants/new"
    POST "restaurants"
  ```

- A visitor can see the details of a restaurant, with all the reviews related to the restaurant.

  ```bash
    GET "restaurants/38"
  ```

- A visitor can add a new review to a restaurant

  ```bash
    GET "restaurants/38/reviews/new"
    POST "restaurants/38/reviews"
  ```

## Setup

To set up the Rails Stupid Coaching application, follow these steps:

Clone the repository:

```sh
  git clone git@github.com:jotaEmeCortat/rails-yelp-mvp.git
  cd rails-yelp-mvp
```

Install dependencies: Make sure you have Ruby and Bundler installed. Then run:

```sh
  bundle install
```

Set up the database:

```sh
  rails db:create db:migrate db:seed
```

Start the Rails server:

```sh
  rails server
```

Access the application: Open your web browser and go to http://localhost:3000.

## Technologies Used

- Ruby on Rails
- Faker
- Bootstrap
- Simple Form
