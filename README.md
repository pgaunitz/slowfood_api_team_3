[![Build Status](https://semaphoreci.com/api/v1/pierre-1/slowfood_api_team_3/branches/development/badge.svg)](https://semaphoreci.com/pierre-1/slowfood_api_team_3)

# The Slowfood Challenge 
### Authors
[Philip](https://github.com/pgaunitz)
[Anish](https://github.com/Anish2504)  
[Johan](https://github.com/johanbounce)  
[Pierre](https://github.com/pierre-1)  

## Built with
**Front End:** React v.16.12.0 | CSS  
**Back End:** Ruby 2.5.1 | Rails 6.0.2 
**Testing framework:** Rspec 
**Deployed at:** [Netlify](netlify.app/) and [Heroku](https://herokuapp.com/).
## The code   
This project is the backend API for our Slowfood application. The master repository for the Slowfood client side, built with React, can be found [API](https://github.com/pgaunitz/slowfood_api_team_3). [Client](https://github.com/pgaunitz/slowfood-client-team-3).
## Getting started
### Dependencies  
* Ruby
* Rails
* Rspec
* Puma
* Devise
* Pry
* Shouda-Matchers
* Coveralls
* Factory Bot
* Bootsnap

### Setup   
To test this application, fork the repo to your own GitHub account and clone it to your local workspace. </br>
*Note:*Be sure to set up the front end (noted above), in order to fully interact with the application. 
To install all of the dependencies:  
```
$ bundle install 
```
To create a new database with sample data:  
```
$ rails db:create db:migrate db:seed 
```
To run the unit tests:  

```
$ rspec
``` 
  
To start the application and run it on your local host:
```
$ rails s
```

## License  
[MIT-license](https://en.wikipedia.org/wiki/MIT_License)
### Acknowledgement  
- Material provided by [Craft Academy](https://craftacademy.se)

