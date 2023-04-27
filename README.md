# Ruby on Rails + Docker (Compose) template

You can use this project as template for your new rails 7+ applications

## Setup

1. `docker-compose build`
2. `docker-compose run --rm web rails new . --database=postgresql`
3. `docker-compose run --rm web rails db:create`

Now docker-compose file contain 2 services: 
1. Rails web server
2. Postgres database
