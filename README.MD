# Ahabay
The flight booking system. We are using [MEAN Stack](http://mean.io/) to develop the app.

## Prerequisite Technologies
### Linux
* *Node.js* - <a href="http://nodejs.org/download/">Download</a> and Install Node.js.
* *MongoDB* - <a href="https://www.mongodb.org/downloads">Download</a> and Install mongodb.

If you're using ubuntu, this is the preferred repository to use...

```bash
$ curl -sL https://deb.nodesource.com/setup_4.x | sudo -E bash -
$ sudo apt-get update
$ sudo apt-get install nodejs
```

* *Git* - Get git using a package manager or <a href="http://git-scm.com/downloads">download</a> it.

### OSX
* *Node.js* -  <a href="http://nodejs.org/download/">Download</a> and Install Node.js or use the packages within brew or macports.
* *MongoDB* - Follow the tutorial here - <a href="https://docs.mongodb.org/manual/tutorial/install-mongodb-on-os-x/">Install mongodb on OSX</a>
* *git* - Get git <a href="http://git-scm.com/download/mac">from here</a>.

## Prerequisite packages

```
$ npm install -g gulp

$ npm install -g bower
```

## Invoke node with a task manager
To start application run -
```bash
$ gulp
```

Alternatively, when not using `gulp` (and for production environments) you can run:
```bash
$ node server
```
Then, open a browser and go to:
```bash
http://localhost:3000
```

### Running on a different port
You can set the port and start project with one command:
```bash
$ export PORT=3001 && gulp
```

Then, open a browser and change the port number before you visit:
```bash
  http://localhost:3001
```

### Troubleshooting
During installation depending on your os and prerequisite versions you may encounter some issues.
Most issues can be solved by one of the following tips.

#### Update NPM, Bower or Gulp
Sometimes you may find there is a weird error during install like npm's *Error: ENOENT*. Usually updating those tools to the latest version solves the issue.

* Updating NPM:
```bash
$ npm update -g npm
```

* Updating Gulp:
```bash
$ npm update -g gulp
```

* Updating Bower:
```bash
$ npm update -g bower
```

#### Cleaning NPM and Bower cache
NPM and Bower has a caching system for holding packages that you already installed.
We found that often cleaning the cache solves some troubles this system creates.

* NPM Clean Cache:
```bash
$ npm cache clean
```

* Bower Clean Cache:
```bash
$ bower cache clean
```
