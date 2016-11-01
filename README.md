# slackBaby2

Installation
- Install node.js & Heroku
- install using "brew install mongodb"
- make directory using "sudo mkdir -p /data/db"
- give permissions using sudo chown -R `id -un` /data/db

Setup
- Just Fork and clone this repository (if owner then copy and change remote)\
- Change repository name to the name of the app 
- To setup a new dev app run "npm run setup-dev"
- To develop the app run "npm run dev"
- To create a staging environment on heroku use "npm run setup-staging", this will have saved the default auth address to the clipboard but you will need to enter the name of the app plus -staging
- to save use "npm run git"
- to push to staging use "npm run stage-git"

TODO
- solve git ID problem
- Do some interesting stuff

- Create production app from script
- Auto pull production mongoDB into staging and 

