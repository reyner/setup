#Setup instructions
All of this should be done prior to Jan 22. We'll start off the class assuming that you have these things working.

##Get the OS
You'll need either Ubuntu 12.xx or OSX. It's not recommended to use Windows since we won't be able to help you debug if any issues come up.  

###Ubuntu
There are two options, either setting up Ubuntu as a dual boot/primary OS, or running it in a VM. If you don't already have Ubuntu, we recommend setting it up as VM. Follow [these instructions](http://www.psychocats.net/ubuntu/virtualbox).  

###OSX
* Install [Xcode](https://developer.apple.com/xcode/)
* Install [homebrew](http://mxcl.github.com/homebrew/)

##Setting up everything else
* Get Chrome. No link for this since… come on. 
* Get [node](http://nodejs.org/)
* Install express by opening up a terminal and typing in ```npm install express```
* Get a [Github account](https://github.com/)
* Setup the [public/private github ssh key](https://help.github.com/articles/generating-ssh-keys#platform-linux)
* Get a [Heroku account](http://www.heroku.com/)
* Do [steps 1-3](https://devcenter.heroku.com/articles/quickstart) to setup Heroku

##Testing
If you properly created everything, you should be able to open up a terminal and do the following:

```
git clone git://github.com/olinjs/setup.git setup; cd setup;
npm install;
heroku create;
git add *;
git commit -m "my first commit";
git push heroku master;
```

If everything works, you should see a message like

```
...
...
...
Launching... done, v4
       http://<some random thing>.herokuapp.com deployed to Heroku
```

If you navigate to http://\<some random thing\>.herokuapp.com you should see "hello world".