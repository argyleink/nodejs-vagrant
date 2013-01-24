# Awesomebox - Fork
This is my chef+vagrant setup for node.js development. It's currently a
work in progress but out of the box it'll give you

* node.js
* nginx
* mongodb 
* socket.io
* rabbitmq (with the management console enabled)

## Running it
Requires that you have a vagrant box named lucid32 installed.

```bash
git clone git@github.com:jamescarr/nodejs-vagrant.git
cd nodejs-vagrant
git submodule init && git submodule update
vagrant up
```

## Soon!
