## DControl

## Setup project
  heroku addons
  heroku addons:create mongolab:sandbox --app dcontrol
  add buildpack nodejs
  git push heroku master
  heroku config:add --app dcontrol MONGO_URL= <<MONGOLAB_URI>>
  heroku config:add --app dcontrol ROOT_URL=https://dcontrol.herokuapp.com/
  
  
  
