# Udacity Restaurant App Stage 1
---
## Table of Contents

* [Overview](#overview)
* [Specification](#specification)
* [Download](#download)
* [Contributing](#contributing)
* [License](#license)
* [Resources](#resources)

## Overview

In this project, I converted a page to a mobile ready page. Adding responsive design and also accessibility properties for different screen sizes and screen readers. Added offline experience.

### Specification

I have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also didn't include any standard accessibility features, and it didn’t work offline at all. My job was to update the code to resolve these issues while still maintaining the included functionality.

### What do I do from here?

Feel free to fork it on your GitHub or clone it on Git Bash.

1. In folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## contributing:
This repository is the starter code for _all_ Udacity students and minor adjustments added for this project. Therefore, we most likely will not accept pull requests.

## Resources
This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

Matthew Cranford  [Restaurant Reviews App Walkthrough](https://matthewcranford.com/restaurant-reviews-app-walkthrough-part-1-map-api/).

Ryan Waite [Tutorial] (https://www.youtube.com/watch?v=2PY733qFR3A&feature=youtu.be).
Udacity student discussion forums

Paul Kinlan[Google Web Fundamentals](https://developers.google.com/web/fundamentals/codelabs/offline/).

Jake Archibald[The Offline Cookbook](https://jakearchibald.com/2014/offline-cookbook/).

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.
