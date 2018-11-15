# Mobile Web Specialist Certification Course
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, I incrementally converted a static web page to a mobile-ready web application. In **Stage One**, I was given a static design that lacked accessibility, and converted the design to be responsive on different sized displays and accessible for screen reader use. I also add a service worker to begin the process of creating a seamless off-line experience for users.

### Specification

I was provided the code for a restaurant reviews website. The code had a lot of issues. It was barely usable on a desktop browser, much less a mobile device. It also did not include any standard accessibility features, and it did not work off line at all. My job was to update the code to resolve these issues while still maintaining the included functionality.

### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 3000` For Python 3.x, you can use `python3 -m http.server 3000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://127.0.0.1:3000`, and look around for a bit to see what the current experience looks like.
3. I Explored the provided code, and made a plan to implement the required features in three areas: responsive design, basic accessibility and off line use.
4. I Wrote code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). I replaced `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code.



# restaurant-stage-1-master
# restaurant-stage-1-master
