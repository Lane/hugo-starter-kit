# Hugo + Netlify CMS + Travis CI Starter Kit
Super-charged [Hugo](https://gohugo.io) development!

## Features
* Work with SCSS and modern JavaScript using ES6/7, output cross-browser compatible code
* Includes [OpenGraph](http://ogp.me/) for improved SEO
* Use BrowserSync during development for live-reloading and cross-device testing

## Requirements
* [Hugo](https://gohugo.io/) (v0.48 or later)
* [Node.js](https://nodejs.org/) (v8.12.0 or later)

## Getting started
* Fork this repository the repo and clone the fork to your local machine
* Run ``npm install`` to install the necessary NPM packages
* Edit `/static/admin/config.yml` to point to your GitHub repository
* Activate on Travis CI and add `GITHUB_TOKEN`, `GITHUB_USERNAME`, and `GITHUB_EMAIL` environment variables.
* That's it! You're ready to rock, just check the commands section below

## Commands
| Command           | Description
|-------------------|-
| ``npm run build`` | Build a production-ready version of the site (outputs to ``./public``)
| ``npm run serve`` | Start development server (at http://localhost:3000/), watch files for changes, re-build when necessary and auto-reload the browser
| ``npm run clean`` | Purge the ``./public`` directory

## FAQ
### There are no styles
This is intentional - no libraries or default styles are included with this project.

## Contributors
* Forked from starter kit by [Donny Burnside](http://donnyburnside.com/)