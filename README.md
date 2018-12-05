# Usage to build

- cd docker-compose/<br>
- docker-compose build<br>
- docker-compose up -d<br>
- docker-compose ps<br>
- vi config/database.yml<br>
17: password: [your_password]<br>
18: host: db<br>
- docker-compose run web rake db:create

# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
