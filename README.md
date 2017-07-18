# Release Notes

Open Source tools to make your dependents happy and to keep your own dependencies on track.


## About

The goal of the _Release Notes_ project is to provide open source tools and services for working with release notes.


## What problem does this project solve?

Currently most of the open source projects out there do not provide
details of what was added or what has changed when they release a new version.

Furthermore it is not possible to be informed about specific release details of the software
you most likely build your business upon (like security updates, deprecations, minor releases and so on.)

Therefore we worked out an **easy to use**, **human readable** and **machine processable** [schema for release notes](https://github.com/release-notes/release-notes-schema).
Around this spec we build open source tools to interact with release notes in order to:

* Automate release note management
* Manage release note update subscribtions of your dependencies
* Deliver fine grained notifications through the channels you already use
* Let your customers and/or dependents subscribe to your software updates
* Host community release notes in a hub


## Why should I care about release notes?

Because this is an easy way for other people to keep track on what has
changed in your software. [Semantic Versioning](http://semver.org) is a great commitment on
building compatible components in a distributed open source world.
**BUT** it will not tell your dependents whether they have to urgently
upgrade to the next compatible version, eg. in case of an security fix.


## Contribute

Any contribution is welcome.
This project is committed to the following [CODE OF CONDUCT](CODE_OF_CONDUCT.md).

**Open a ticket and**

* give your feedback
* share your current painpoints about release notes
* star this project if you think its useful
* use the tools and report bugs
* request new features

**Reach out by email**

Send me an email at alrik.zachert@gmail.com and let's discuss how you can involve.

**Submit a PR in order to**

* fix a bug
* improve the docs
* improve test coverage


## Project Repositories

- [Release Notes Specification](https://github.com/release-notes/release-notes-spec)
- [Release Notes JSON-Schema Definitions](https://github.com/release-notes/release-notes-schema)
- [Release Notes Node.js Reference Implementation](https://github.com/release-notes/release-notes-node)
- [Release Notes CLI](https://github.com/release-notes/release-notes-cli)
- [Release Notes Hub](https://github.com/release-notes/release-notes-hub)
- [Release Notes JS Coding Styles](https://github.com/release-notes/eslint-config-release-notes)
