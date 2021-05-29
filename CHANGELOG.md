# Changelog

Notable changes to this project are documented in this file. The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/) and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

Breaking changes:

New features:

Bugfixes:

Other improvements:
- Stop mangled 'Compiled ModuleName' output (#228 by @JordanMartinez)
- Update dev instructions: create valid symbolic link across OSes (#226 by @JordanMartinez)
- Added a changelog (#229 by @JordanMartinez)

## [v2021-05-29.1](https://github.com/purescript/trypurescript/releases/tag/v2021-05-29.1) - 2021-05-29

This release officially adds support for PureScript 0.14 to Try PureScript, among many other (largely internal) improvements and updates.

* Updated the compiler and package set for PureScript 0.14 (#209, #213, #224 by @thomashoneyman, #223 by @JordanMartinez)
* Updated local development instructions (#221 by @JordanMartinez, #225 by @thomashoneyman)
* Added support for loading files from GitHub repositories and migrated examples into the Try PureScript repository (#218 by @thomashoneyman)
* Migrated the client to Halogen from JQuery (#215 by @thomashoneyman)
* Migrated the client to `argonaut-codecs` from `foreign-generic` (#212, #217 by @thomashoneyman)
* Migrated the client to `Aff` from `ContT` (#208 by @thomashoneyman)
* Added fixtures to test API responses (#211 by @thomashoneyman)
* Removed unused pragmas, imports, and definitions from server code (#206 by @thomashoneyman)
* Allowed form submission in the Try PureScript iframe (#203 by @mikesol)
* Switch to use a svg favicon with ico fallback (#191 by @milesfrain)
* Implement `encode` in PureScript instead of in FFI (#186 by @maxdeviant)

## [v2020-07-11.1](https://github.com/purescript/trypurescript/releases/tag/v2020-07-11.1) - 2020-07-11

* Enable automated SSL certificate renewal (#184, @hdgarrood)
* Remove unused `parsec` dependency (#178, @hdgarrood)
* Only listen on 127.0.0.1 (#177, @hdgarrood)

## [v2020-05-26.1](https://github.com/purescript/trypurescript/releases/tag/v2020-05-26.1) - 2020-05-26

* Update to PureScript v0.13.8 (#175, @hdgarrood
* Make the whole package set available (#173, @hdgarrood, @thomashoneyman)
* Do away with version numbers (#176, @hdgarrood)

## [v0.13.7](https://github.com/purescript/trypurescript/releases/tag/v0.13.7) - 2020-05-03

* Fix help link (#165, @hdgarrood)
* Update API documentation in readme (#168, @hdgarrood)

## [v0.13.6](https://github.com/purescript/trypurescript/releases/tag/v0.13.6) - 2020-05-03

* Update to v0.13.6 of the PureScript compiler
* minor tweaks to get deploys working

## [v0.13.5](https://github.com/purescript/trypurescript/releases/tag/v0.13.5) - 2020-05-02

* Update to v0.13.5 of the compiler (@natefaubion)
* Remove backends, serve individual modules on demand (@natefaubion, @gabejohnson, #128, #136)
* Host the client ourselves rather than using GH pages
* Put all source files in one branch (@gabejohnson, #135)
* Fix gist navigation within the iframe (@natefaubion, #140)
* Use different sourceURL syntax per warnings (@natefaubion, #141)
* Switch to spago for managing PS dependencies (@hdgarrood, #147, #150)
* Build the frontend in CI (@hdgarrood, #152)
* Mostly automated deployments (@hdgarrood)

## [v0.12.0-rc.5](https://github.com/purescript/trypurescript/releases/tag/v0.12.0-rc.5) - 2020-05-02

Testing deployment

## [v0.12.0-rc.4](https://github.com/purescript/trypurescript/releases/tag/v0.12.0-rc.4) - 2020-05-02

Testing deployment

## [v0.12.0-rc.3](https://github.com/purescript/trypurescript/releases/tag/v0.12.0-rc.3) - 2020-05-02

Testing deployment

## [v0.12.0-rc.2](https://github.com/purescript/trypurescript/releases/tag/v0.12.0-rc.2) - 2020-05-02

Testing deployment

## [v0.12.0-rc.1](https://github.com/purescript/trypurescript/releases/tag/v0.12.0-rc.1) - 2020-05-02

Mostly for testing the new deployment mechanisms.

## [v0.11.7](https://github.com/purescript/trypurescript/releases/tag/v0.11.7) - 2017-11-30

Update to 0.11.7 (@Thimoteus)

## [v0.11.6.1](https://github.com/purescript/trypurescript/releases/tag/v0.11.6.1) - 2017-09-01

Return warnings from API

## [v0.11.6](https://github.com/purescript/trypurescript/releases/tag/v0.11.6) - 2017-07-11

Updates for the v0.11.6 compiler

## [v0.11.2](https://github.com/purescript/trypurescript/releases/tag/v0.11.2) - 2017-04-02

Update to 0.11.2 compiler

## [v0.11.1](https://github.com/purescript/trypurescript/releases/tag/v0.11.1) - 2017-04-01

Updates for 0.11.1 compiler.

## [v0.10.5](https://github.com/purescript/trypurescript/releases/tag/v0.10.5) - 2017-01-16

Update compiler and add basic type search

## [v0.10.4](https://github.com/purescript/trypurescript/releases/tag/v0.10.4) - 2017-01-02

Update to compiler v0.10.4

## [v0.10.3](https://github.com/purescript/trypurescript/releases/tag/v0.10.3) - 2016-12-18

Update to 0.10.3, use JSON errors.

## [v0.10.2](https://github.com/purescript/trypurescript/releases/tag/v0.10.2) - 2016-11-11

New version using compiler v0.10.2

## [v0.9.1.1](https://github.com/purescript/trypurescript/releases/tag/v0.9.1.1) - 2016-06-17



## [v0.9.1](https://github.com/purescript/trypurescript/releases/tag/v0.9.1) - 2016-06-17



## [v0.8.2.0](https://github.com/purescript/trypurescript/releases/tag/v0.8.2.0) - 2016-03-11

Updates for v0.8.2 compiler