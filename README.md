# codeberry-webserver-static

This is a simple Node.js webserver that sends a hello world response

## How to use
- [install node.js](https://nodejs.org) on your machine
- [install git](https://git-scm.com/) on your machine (so that on Windows you can use Bash commands)
- open up a Command line / terminal to a folder you'd like to contain your projects
- `$ git clone https://github.com/freegyes/codeberry-webserver.git`
- `$ cd codeberry-webserver`
- `$ npm start`

## How to tell if it is working
- on your terminal it should say: `Server running at http://127.0.0.1:3000/`
- visit [http://127.0.0.1:3000](http://127.0.0.1:3000) where you should see the 'Hello world'

## How to stop the server
- in your terminal / command line press <kbd>ctrl</kbd> + <kbd>c</kbd> to exit the process and free up the port in use
- (<kbd>ctrl</kbd> + <kbd>z</kbd> will only suspend it and when you try to run the server again, it will give an address in use error like the following: `Error: listen EADDRINUSE 127.0.0.1:3000`)
