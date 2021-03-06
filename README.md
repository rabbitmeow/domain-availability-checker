# Domain Availability Checker

For checking availability of domain in [GoDaddy](https://godaddy.com) using [selenium](https://selenium.dev/) based on your own wordlist

## Demo

![demo](demo.gif)

## Getting Started

Are you tired checking domain availability one by one ? You come in right place. This app will allow you to check domain based on your wordlist. Read following guide to setup your app.

### Prerequisites

- Make sure latest [NodeJS](https://nodejs.org/) is installed
- To running this app, you need to install browser(chrome) in the machine. For VPS (e.g digitalocean) with Ubuntu, you can run : `apt-get install chromium-browser`

### Config

Take a look at `config.js`. There is all config for this app

- show_browser : set `true` for showing browser window, set to `false` for headless browser
- show_log: set `true` for showing log in console
- tld: add your TLD that will be checked

### Installing

- Clone this repo
- Make sure you have the latest version of NodeJs
- Run `npx npm-check-updates -u` to check the latest version of dependencies (especially for chromedriver)
- Run `npm install` to installing all dependencies
- Add your word list into `wordlist.txt`
- Run `node index.js`
