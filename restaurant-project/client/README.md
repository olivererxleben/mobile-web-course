# Mobile Web Specialist Certification Course
---
#### _Three Stage Course Material Project - Restaurant Reviews_

Original Source Code comes from https://github.com/udacity/mws-restaurant-stage-1

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and make start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.

### Conclusion: Stage 1

1. Static web site was converted to the design to be responsive.
2. Added new accessibility features.
3. The web site can work offline first.

### Changes for Development Process

I added NPM based approach:

Start dev webserver via 

    npm start


## Stage 2 + 3

After cloning, navigate into *client*-folder and execute the following:

    npm install 

After some time you have all dependencies and tools installed. Use

    npm start 

to start development server. Performance and PWA tests can be triggered via command line: 

    npm run audit 

will start lighthouse cli. NOTE: you need to have web-server running and bound at http://localhost:8000 


Application uses development server provided by udacity. Its added at *server* folder for convenience. Check out intructions in that readme for more information. :)

## Stage 3

Refactored application alot. 

updated 

    npm run audit

will now also start the gulp webserver and run lighthouse cli afterwards

### Other files

Icon used and modified in manifest:

https://www.flaticon.com/free-icon/restaurant-cutlery-circular-symbol-of-a-spoon-and-a-fork-in-a-circle_45332#term=restaurant&page=1&position=7

