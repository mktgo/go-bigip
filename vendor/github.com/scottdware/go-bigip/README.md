## go-bigip
[![GoDoc](https://godoc.org/github.com/mktgo/go-bigip?status.svg)](https://godoc.org/github.com/mktgo/go-bigip) [![Travis-CI](https://travis-ci.org/scottdware/go-bigip.svg?branch=master)](https://travis-ci.org/scottdware/go-bigip)
[![Go Report Card](https://goreportcard.com/badge/github.com/mktgo/go-bigip)](https://goreportcard.com/report/github.com/mktgo/go-bigip)
[![license](http://img.shields.io/badge/license-MIT-red.svg?style=flat)](https://raw.githubusercontent.com/scottdware/go-bigip/master/LICENSE)

A Go package that interacts with F5 BIG-IP systems using the REST API.

Some of the tasks you can do are as follows:

* Get a detailed list of all nodes, pools, vlans, routes, trunks, route domains, self IP's, virtual servers, monitors on the BIG-IP system.
* Create/delete nodes, pools, vlans, routes, trunks, route domains, self IP's, virtual servers, monitors, etc.
* Modify individual settings for all of the above.
* Change the status of nodes and individual pool members (enable/disable).

> **Note**: You must be on version 11.4+! For the features that deal with internal data groups, you must be running version 11.6+!

### Examples & Documentation
Visit the [GoDoc][godoc-go-bigip] page for package documentation and examples.

Here's a [blog post][blog] that goes a little more in-depth.

### Contributors
A very special thanks to the following who have helped contribute to this software, especially:

* [Kenneth Maglio](https://github.com/kenmaglio)
* [Adam Burnett](https://github.com/aburnett)
* [Michael D. Ivey](https://github.com/ivey)

[godoc-go-bigip]: http://godoc.org/github.com/mktgo/go-bigip
[license]: https://github.com/mktgo/go-bigip/blob/master/LICENSE
[blog]: http://sdubs.org/go-big-ip-or-go-home/
