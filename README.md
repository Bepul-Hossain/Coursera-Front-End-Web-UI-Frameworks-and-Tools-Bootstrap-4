```step 1:
Step 1: Setting up development environment

create a folder 'coursera'
coursera> npm init
coursera> npm install lite-server --save-dev

open package.json
{
  "name": "coursera",
  "version": "1.0.0",
  "description": "front end",
  "main": "index.html",
  "scripts": {
    "start": "npm run lite",
    "test": "echo \"Error: no test specified\" && exit 1",
    "lite": "lite-server"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/Bepul-Hossain/coursera.git"
  },
  "author": "",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/Bepul-Hossain/coursera/issues"
  },
  "homepage": "https://github.com/Bepul-Hossain/coursera#readme",
  "devDependencies": {
    "lite-server": "^2.5.4"
  }
}

coursera> create 'index.html' file on root folder
coursera> npm start
```
