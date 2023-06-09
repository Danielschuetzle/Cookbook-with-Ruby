# 🍳 Cookbook - Your Go-To Recipe Management App 🍳

Welcome to Cookbook! 🚀 This project is a recipe management application, created using the robust Ruby on Rails framework. It has been designed to store, manage, and display your favorite recipes.

Cookbook is your own digital recipe book. It aims to keep a list of your favorite recipes, letting you `list` them, `add` new ones, and `delete` ones you no longer need.

## 🔑 Features

- **Recipe Management 📝:** Users can create, update, delete, and view their recipes with an easy-to-use interface.
- **User Authentication 🔒:** Users can sign up, log in and log out with ease, ensuring a secure user experience.
- **List Recipes 📃:** Users can list all their saved recipes, making it easy to choose what to cook next.
- **Add Recipes 🍽️:** Users can add new recipes to their cookbook, ensuring their favorite meals are never forgotten.
- **Delete Recipes 🗑️:** Users can remove recipes from their cookbook when they no longer need them.

## 🚀 Getting Started

This section will guide you through the local setup.

### Prerequisites

Make sure you have the following installed:

- Ruby 2.7.0 or later
- Rails 6.0.0 or later
- PostgreSQL

### Installing

```bash
# Clone this repository locally
git clone https://github.com/username/cookbook.git
cd cookbook

# Install dependencies
bundle install
yarn install

# Setup the database
rails db:create db:migrate

# Start the server
rails server




Once the server is running, you can visit http://localhost:3000 to view the app!

Remember that this project follows the MVC pattern - Model (basic object manipulation), View (displaying information and asking for user information), and Controller (fetching and storing model data, instructing the view to interact with the user).
