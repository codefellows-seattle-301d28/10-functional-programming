# Functional Programming Lab

**Author**: George and Jeremu
**Version**: 1.0.0 (increment the patch/fix version number up if you make more commits past your first submission)

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->
New admin page counts words, words by author and gets author list

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
Git clone, run npm i, run node and your postgres Server

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->

10-functional-programming
└──driver-navigator
  ├── .eslintrc.json
  ├── .gitignore
  ├── LICENSE
  ├── README.md
  ├── node_modules
  ├── package-lock.json
  ├── package.json
  ├── public
  │   ├── data
  │   │   └── hackerIpsum.json
  │   ├── admin.html
  │   ├── index.html
  │   ├── new.html
  │   ├── scripts
  │   │   ├── article.js
  │   │   └── articleView.js
  │   ├── styles
  │   │   ├── base.css
  │   │   ├── layout.css
  │   │   └── modules.css
  │   └── vendor
  │       ├── scripts
  │       │   └── highlight.pack.js
  │       └── styles
  │           ├── fonts
  │           │   ├── icomoon.eot
  │           │   ├── icomoon.svg
  │           │   ├── icomoon.ttf
  │           │   └── icomoon.woff
  │           ├── default.css
  │           ├── icons.css
  │           ├── normalize.css
  │           └── railscasts.css
  └── server.js

## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples: -->

12-11-2017  9:00AM - Added linking to use the .map function and IIFE statements to make articles load
12-11-2017  10:00AM - Added functions for counting
12-11-2017  1:00PM - Troubleshot and added handlebars template


## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
George and Jeremy
Credit to Kevin/Roger for help with handlebars template
