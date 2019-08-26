Satorix Passenger buildpack
===========================

Use [Phusion Passenger](https://www.phusionpassenger.com) in a buildpack compatible app.

Requires
--------

You must also use the [Ruby Buildpack](https://github.com/heroku/heroku-buildpack-ruby) with this buildpack since Passenger has tools based on Ruby.

Usage
-----

Add the buildpack to a `.buildpacks` configuration in the root of the application directory to install the `passenger` tools.

Configuration
-------------

* Defaults to 64-bit Linux binary Passenger version 6.0.2 for Heroku runtime
* `PASSENGER_BIN_URL` set the source URL for the terraform binary
* Expects a `*.zip` file as [distributed by Phusion](https://github.com/phusion/passenger/releases)
