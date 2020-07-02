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


When you are stuck in webpacker errors, and you think you are in an ocean of problems, 
I have some awesome commands for you. Just close your eyes and in the app directory itself, type this stuff :

1. sudo apt remove cmdtest
2. sudo apt remove yarn
4. curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
5. echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
6. sudo apt-get update && sudo apt-get install yarn

.....aaaannnnddd boom! No errors now.
Thank me later!