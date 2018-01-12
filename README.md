<p align="center">
  <img src="https://release-notes.com/android-chrome-512x512.png" alt="Release Notes">
</p>
<h1 align="center">Release Notes</h1>
<p align="center">
  <em>
      This is the cockpit repository of the release notes platform. :rocket:
      Here you'll find all resources around our platform, our vision and mission statement and how you can get involved :neckbeard:.
  </em>
  <br>
  :tada: Hosted changelog pages and release announcements for open source projects :tada:
  <br>
  :clipboard: Lightweight release notes yml schema specification :clipboard:
  <br>
  :neckbeard: Cli tools for release notes management :neckbeard:
  <br>
  <a href="https://release-notes.com" target="_blank">https://release-notes.com</a>  
</p>

## About

Release Notes is an open source platform for automated release notes management around traditional CHANGELOG files
and our generalized [Release Notes Schema Specification](https://github.com/release-notes/release-notes-spec) via 
[CLI tools](https://github.com/release-notes/release-notes-cli). Our [node lib](https://github.com/release-notes/release-notes-node) is the first implementation of the
[JSON schema definition](https://github.com/release-notes/release-notes-schema) that should make porting to other languages easy.

**AND** you can publish your `CHANGELOG.md` or `release-notes.yml` on our open source [hub](https://github.com/release-notes/release-notes-hub),
that provides free hosted changelog pages for open source projects. We also have badges :tada: and an API _(at least one endpoint)_ :tada:

Check it out on https://release-notes.com.

## Goal

The goal of the _Release Notes_ project is to build a great ecosystem around releasing things.

## What problem does this project solve?

Currently most of the open source projects out there do not provide
details of what was added or what has changed when they release a new version.

Also there is no formal changelog/release notes standard and just a few best practise approaches out there.

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

Release notes are the best way to manifest and communicate updates (eg. bug fixes, new release, new publication, etc.).
Providing release notes makes it easy for other people to keep track on what has changed in your software.

Checkout our [Awesome Changelog](https://github.com/release-notes/awesome-changelog) for a curated list
of awesome CHANGELOG.md's and tools around release notes management.

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
