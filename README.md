Project - Dev Wiki
=============

This Wiki is about learning to contribute to MRO Project. MRO is a web-based video game providing ways to implements role playing games (dungeon and dragons like) and playing it over the internet (web, mobile or desktop). It's targeting at Game Masters, Players and Casual Players.



## Contents

* [Reminder](#Reminder)
* [Getting started](#Getting-started)
* [Conventions](#Conventions)
* [Contribution](#Contribution)



## Reminder

Tools
* Backlog (Trello) at https://trello.com/b/vMsZjqS1/
* Source (GitHub) at https://github.com/MRO-Org/
* Host (Heroku) at https://dashboard.heroku.com/apps

Projects
* Game
    * Source at https://github.com/MRO-Org/mro
    * Run at https://project-myrpgonline.herokuapp.com/play
* WebSite 
    * Source at https://github.com/MRO-Org/mro-website
    * Run at https://project-myrpgonline.herokuapp.com/



## Getting started

* Install (if you don't have them):
    * [GitHub](https://desktop.github.com): download and install the latest
    * [SublimeText](http://www.sublimetext.com): download and install
    * [Node.js](http://nodejs.org): download and install
    * [Git](https://git-scm.com/download/win): download and install the latest
        * WARNING: choose 'Use Git from the Windows Command Prompt' during install
    * [Brunch](http://brunch.io): `npm install -g brunch@1.8.5` from command line (WIN+R,'cmd')
    * [Bower](http://bower.io): `npm install -g bower@1.6.4` from command line (WIN+R,'cmd')
* Get the project
    * Create an account on GitHub if necessary
    * Open project page https://github.com/DamienFremont/project-myrpgonline
    * Click on 'Clone in Desktop' button
    * Confirm 'launch application' popup
    * ...then GitHub app launch on your desktop
    * ...and wait for it to finish project download
    * The project must be in your <user folder>/Documents/GitHub/project-myrpgonline
* Run:
    * got to project scripts folder
    * click on install-1.bat then click on install-2.bat (only the first time, closed it manualy when it's finished)
    * click on start-1-client.bat and start-2-server.bat
        * a command line console window pop in
        * ...wait until the console displays 'started'
* Test:
    * open your browser at [http://localhost:3333/](http://localhost:3333/)
* Learn:
    * `public/` dir is fully auto-generated and served by HTTP server.  Write your code in `app/` dir.
    * Place static files you want to be copied from `app/assets/` to `public/`.
    * Languages: [HTML](http://www.w3schools.com/html/), [CSS](http://www.w3schools.com/css/), [JavaScript](http://www.w3schools.com/js/)
    * Frameworks: [AngularJs doc](https://docs.angularjs.org/guide), [Bootstrap doc](http://getbootstrap.com/getting-started/#examples), [Express.js doc](http://expressjs.com/guide/routing.html)
    * Tools: [Brunch site](http://brunch.io), [Node.js doc](http://www.tutorialspoint.com/nodejs/)



## Conventions
### *Coding best practices.*

* Use JavaScript for scripts
* Use CSS for styles
* Use HTML for templates

![ScreenShot](resources/mean-logo.png)

A complete stack for Javascript, comprised of MongoDB, Express, Angular, and Node.

The MEAN stack is a potent new concoction of javascript-flavored tooling, services, and frameworks that make modern, single-page application design a breeze:

* Use Brunch for build
* Use NodeJs for Server



## Contribution

How to contribute ?

You can contribute by :
* testing the project at https://project-myrpgonline.herokuapp.com/
* participating to the project code base. First read the Getting Started page. After that, you can play with the project, then push some code.
