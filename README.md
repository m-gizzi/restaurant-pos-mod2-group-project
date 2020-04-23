# README

Quick links:

Demo: https://www.youtube.com/watch?v=pxwqxB_u3uY

__________________________________________

Orderli is a simple Rails based restaurant point-of-sale (POS) system.  It has some basic login functionality using cookies, as well as the ability to track orders, calculate totals and purchase numbers, and track paid orders vs. open and refunded.

### Prerequisites

The menu is built in through the seed file. You can add more there if you wish, there is also the ability to add from within the app itself. Make sure to follow the server side instructions to migrate the database once you clone it.

### Built With
* Ruby
* Rails
* SQLite3
* Session cookies

### Server-Side Install Instructions
1. Run ```bundle install```
2. Run ```rake db:create```
3. Run ```rake db:migrate```
4. Run ```rake db:seed```
5. Run ```rails s```
### Client-Side Install Instructions
1. Open your localhost

### The App

There is a default account provided in the seed file to login without signing up.  Simply use the PIN 1234 when logging in.

### To-dos

Given more time to come back to this, icebox things to experiment with adding are:

1. Wire up a payment processor
2. Add admin functionality to menu editing and refunding checks

### Author

Matthew Gizzi, Sam Zandi ([@sammyzandi](https://github.com/sammyzanny)), Zach Weber ([@ztw17](https://github.com/ztw17)), Lindsay Mecher ([@lindsayMecher](https://github.com/lindsayMecher))
