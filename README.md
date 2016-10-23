# README

* Based on https://www.nopio.com/blog/react-rails-part-1-tutorial/

* Ruby version

* System dependencies

* Configuration
Remove Turbolinks from Gemfile and from application.js
Remove Turbolink call from application.html.erb
Add "config.react.variant = :development" to config/environments/development.rb
after the do line.
Run $rails g react:install to automatically setup javascripts in assets and confiugre includes
Set up application.scss with @import Boostrap SASS and Sporkets
Generate Controller dashboard index
Generate resource event
rake db:migrate
Add root path and the api namespace


* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
# react-nopio
