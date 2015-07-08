Gazelle
=======

[![Build Status](https://travis-ci.org/meteor-gazelle/meteor-gazelle.svg?branch=master)](https://travis-ci.org/meteor-gazelle/meteor-gazelle)

Gazelle is a web framework geared towards private BitTorrent trackers.
Gazelle is written in Javascript, using the Meteor framework.

_Note_: This version of Gazelle is under active development.

Contributing and Communications
------------

Be sure all code written follows the [Meteor style guide](https://github.com/meteor/meteor/wiki/Meteor-Style-Guide), and has the appropriate test methods.

Communication
-------------
* The [Issues and Milestones](https://github.com/meteor-gazelle/meteor-gazelle/issues) contains items that need to be worked on. Check there for a general overview of what needs to be worked on.
* IRC
  * &#35;gazelle on irc.what-network.net is the official meteor-gazelle development channel. All questions should be directed there.
  * If you are looking for something to work on, ping a Core team member (operators in #gazelle).

Submitting a pull request
-------------------------
* (Fork)[https://github.com/meteor-gazelle/meteor-gazelle/fork] the repository, and switch to a new branch using `git checkout -b <branch_name>`.
* Make your changes, and submit a (new pull request)[https://github.com/meteor-gazelle/meteor-gazelle/compare]. Be detailed in the pull request's description.
  * If your pull request applies to a milestone and/or issue, be sure to select the appropriate one.
* The new pull request will be broadcasted in #gazelle, and the Core team will review it and leave feedback.


Coding Standards
----------------
All code follows the [Meteor style guide](https://github.com/meteor/meteor/wiki/Meteor-Style-Guide).

Dependencies
------------
* [Meteor](https://www.meteor.com/) 

Installation
------------
After [installing Meteor](https://www.meteor.com/install), clone this repository, create a settings.json file based off of the settings template and run 'meteor run --settings setttings.json'. 

[Vagrant](https://github.com/meteor-gazelle/vagrant) allows for a simple installation for a clean development environment. The readme provides detailed instructions for how to set it up. Vagrant is good if you'd like to run meteor-gazelle in a Debian environment.

