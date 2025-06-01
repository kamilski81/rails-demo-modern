# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation 
** Create a role inside DB on local machine to match the database name in `config/database.yml`:
```psql
psql -p 1717 -U postgres; (If using DBNgin, no password)
create role "rails_modern" superuser login createdb;
```

** Then, create the databases:
```sh
bundle exec rake db:create; # Wil create development & test databases
```

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

