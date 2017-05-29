![OneExchangeLogo](img/one-exhcange-logo.png)

**One Exchange aka Pery Exchange**
===================
One Exchange is an application that convert currency.

It's a first app to a [One Bit Code Bootcamp](http://onebitcode.com/) and a so cool!

### Technologies used
- Ruby 2.3.3
- Rails 5.0.1
- PostgreSQL
- Docker
- Docker Compose
- Codeship
- Heroku

## Run with Docker
```
git clone https://github.com/perylemke/one_exchange.git
docker-compose build
docker-compose run --rm website rake db:create db:migrate
docker-compose up
```

## Run in Production

[Pery Exchange](http://pery-exchange.herokuapp.com/)

## Run tests
```
docker-compose run --rm website rspec
```
