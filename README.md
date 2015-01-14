# meteorstorm

Just a "quick" meteor test project.

Ok so I _think_ the setup procedure is now:
* Git clone this repository
* vagrant up
* You'll probably then need to git init _inside the VM_ because Meteor and Windows and oh god.
* Therefore you'll also need to add a remote, set upstream, tell git your name & email, all that sort of stuff.
* Hopefully I'll get round to adding (most of) that to the provisioning script one day.
* Let's see if it basically works first.

_So far I think the lesson is if you're running Windows, don't use Meteor yet. Wait till they support it properly. (Longer version: Currently it requires using Vagrant, with some extra mystery magic setup steps, and even then you can only run git from within your VM, not from your host machine, so you have to configure a git setup all over again, and, and, and I JUST WANT TO MAKE MY APP GODDAMMIT.)_
