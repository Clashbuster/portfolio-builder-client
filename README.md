# Portfolio Builder Lite

Hello! This is the github repo for the client-side of Portfolio Builder Lite.

* As a user, you can:
    sign in with your current email or create a new user account
    view, create and edit items in your portfolio
    view your finalyzed portfolio!

## Prerequisites ## 

To use: Please clone down this repository by copying the link and running ```git clone <repo_url>``` in your terminal. 

This also requires that you have a node package manager ```npm``` or ```yarn``` installed. Please see documentation before getting started. 

Please also make sure to clone down the backend API, which requires Ruby and PostGreSQL: https://github.com/devincloudkelly/portfolio-builder-backend

Frontend:
```javascript
$ npm install

$ npm start
```

Backend:
```ruby
$ bundle install
$ rails db:create
$ rails db:migrate
$ rails db:seed //if you want dummy data

$ rails s //start server 

```

## Image credits ## 

Logos displayed through the app were designed by DinosoftLabs. You can find more of their work here: https://www.flaticon.com/authors/dinosoftlabs