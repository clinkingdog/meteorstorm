# meteorstorm

Just a "quick" meteor test project.

Ok so I _think_ the setup procedure is now:
* Git clone this repository
* vagrant up
* git config --global user.email "your@email.address"
* git config --global user.name "Your Name"
* Put your private & public keypair in ~/.ssh and chmod 0700 the private one
* _Looks like the other git config steps, which should happen in vagrantup.sh, aren't happening automatically, so do them manually for now_

_So far I think the lesson is if you're running Windows, don't use Meteor yet. Wait till they support it properly. (Longer version: Currently it requires using Vagrant, with some extra mystery magic setup steps, and even then you can only run git from within your VM, not from your host machine, so you have to configure a git setup all over again, and, and, and I JUST WANT TO MAKE MY APP GODDAMMIT.)_
