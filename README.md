# Pup-Pals

A platform for dog owners to create and join dog meet-up events. This web application is built with NodeJS, Express, ReactJS, socket.io, AWS-S3 and Postgresql.

This repository is the production build of the web application. For the development build, please see:
[Production Build Repository](https://github.com/aWildOtto/pup-pals)

[Deployeded Version](https://puppals.herokuapp.com/)



### Usage

Any user can browse events, user profiles, and dog profiles belonging to users, as well as search for events in the search page, narrow them down by time range and location and see the filtered results real-time.

Logged-in users can RSVP to events, cancel their attendance, or participate in the real-time message board of specific events. Logged-in users can also update their personal status, as well as upload picture updates on the individual profiles of their dogs.

### Getting Started

1)Clone this repository and install the dependencies individually.
2)Create .env file following the format of .example.env file present in the repository.
3)Run migrations and seed files.


To start the express server:
```
cd server
npm run start
```

You are all set, open the web app on your browser: http://localhost:3000/

### Screenshot

### Dependencies

* aws-sdk
* express
* express-socket.io-session
* geocoder
* knex
* moment
* socket.io
* ejs
* fullcalendar


### Contributors

* [Caitlin](https://github.com/caitlinquon)
* [Donald](https://github.com/donaldma)
* [Otto](https://github.com/aWildOtto)
* [Ti](https://github.com/nombiezinja)

Disclaimer: this project is meant for learning purpose only, please do not use.