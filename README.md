## DControl

## Setup project
  heroku addons
  heroku addons:create mongolab:sandbox --app dcontrol
  heroku buildpacks:set https://github.com/AdmitHub/meteor-buildpack-horse.git  --app dcontrol
  git push heroku master
  heroku config:add --app dcontrol MONGO_URL= <<MONGOLAB_URI>>
  heroku config:add --app dcontrol ROOT_URL=https://dcontrol.herokuapp.com/
  
  
  
https://github.com/AdmitHub/meteor-buildpack-horse.git