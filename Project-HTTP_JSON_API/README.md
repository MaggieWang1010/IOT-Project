Project------>HTTP JSON API + Node.js + Time Server + Parsing Time
======
## Step 1: Install Node.js on Ubuntu
* Set up Ubuntu
* How to Check your Ubuntu Version
$ lsb_release -a
* Enable the NodeSource repository by running the following curl
$ curl -sL https://deb.nodesource.com/setup_10.x | sudo -E bash -
* Install Node.js and npm
$ sudo apt install nodejs
* Verify that the Node.js and npm were successfully
$ node --version
$ npm --version
## Step 2: Study Time Server and try to display current time in ISO format.
## Step 3: Study JSON
## Step 4: Study HTTP JSON API Server
## Step 5: Modify HTTP JSON API Server to support these requests from the client side

* Parse Current Time

>> http://localhost:8000/api/parse_currenttme
    
* The browser displays current time in this way

>> {"year":2021,"month":09,"date":24,"hour":16,"minute":09}
    
* Unix Time of Current Time

>> http://localhost:8000/api/unix_currenttme
    
* The browser displays current time in a way similar to

>> {"unixtime":1376136615474}

###
Mode details in [Slides](https://docs.google.com/presentation/d/1GXfRdK0zRuHOAz-_yRlTmTiZYeKkilCv7neOqCp0rZI/edit?usp=sharing)
