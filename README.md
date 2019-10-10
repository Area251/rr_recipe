# :warning::gem: Reactive Gem Recipes :book::ramen:

> *This app was based on a tutorial.* !

Application to store your favorite recipes and displays them, the project was built with Ruby on Rails as Backend and React.js as Front End.

## Getting Started

Clone this repo to your computer.

### Prerequisites

You will need...

- Ruby on Rails
- Yarn
- PostgreSQL
- Node (npm)

### Installing

Move into the project folder and run the next commands.

First, we have to install the rails dependencies:
```
bundle install
```
When the installation finish it's time to create the database and run the migrations:
```
rails db:create
rails db:migrate
# Optional, you can run the seed command to add test data to your database.
rails db:seed
```
and finally, run the next:
```
yarn install
```

## Authors

* **Roy Derks** - *Initial work* - [DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-display-data-from-the-digitalocean-api-with-react)

## Other
 To see the full tutorial you can found it here: [How to create a Ruby on Rails App that stores with a React Front-end](https://morioh.com/p/21a05899ea10)