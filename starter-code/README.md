# Kilovolt Blog

**Author**: Alchemy Code Lab 301 Day Class - Fall 2017

**Version**: 1.0.0

## Overview
A responsive blog app for Alchemy Code Lab students to document their experience during code school.

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
To run this project locally, `fork` and `clone` this repo.
- Fork it to your GitHub account.
- In your terminal: `git clone <your-fork-url>` and `npm install` to install the necessary npm packages

Do your work on a feature named branch, for example "responsive-header"
- In your terminal: `git checkout <feature-name>`
- We recommend using a live updating server to streamline your development process. We use [live-server](https://www.npmjs.com/package/live-server) installed with npm. 

Make sure your project is still passing the linter.
- In your terminal, `cd` into the project repo and run `eslint .`

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
Front end: 

Our JS is structured following MVC. Script folders/files are named to reflect which component they relate to: `articleView.js` or `models/Article.js`. 

Styles are structured following SMACCS.

Libraries used include: jQuery (for DOM manipulation, AJAX), HandlebarsJS (for HTML templates), NormalizeCSS (for CSS reset).

Back end:

We are using ExpressJS and Node to create a server.