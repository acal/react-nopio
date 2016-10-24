# README

* Based on https://www.nopio.com/blog/react-rails-part-1-tutorial/

* Ruby version

* System dependencies
Gem react-rails: https://github.com/reactjs/react-rails

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
Create api folder under app/controllers and move events_controller to that folder
Update the events_controller beginning with module Api and set up index method to return jason format
Change index.html.erb in the dashboard folder to call react component with erb.
Delete the unnessessary events folder under app/views
Create a React component called event_applications.js.jsx under app/assets/javascripts/components
Create events.js.jsx
Create seeds.rb


* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions
* rails server -b $IP -p $PORT

* ...
# react-nopio
