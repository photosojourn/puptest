## Introduction

Puptest is a quick tool I have put together inorder to help with testing of
Puppet 5 in docker container. The tool allows you to easily build an image
using the latest Puppet 5 nightly against both Centos and Ubuntu. In addtion
to Puppet 5 version 4 is also supported in order to help with bug investigation.
This setup is designed for use in a "masterless" setup such as during module 
development and add hoc rpec and serverspec testing.

## Installation

Assuming you have Docker installed you just have to clone the repo and run
the tool with the right inputs as shown below.

# Usage

This tool has three options which are listed below

* -b Flag used to determine wether the Docker image need to built such as during first run (Optional)
* -v A hyphenated string showing version and OS. I.e puppet5-centos or puppet4-ubuntu (Required)
* -d A full path to a directory you wish to mount at /puppet i.e /home/user/puppet-test-code (Optional)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

MIT License. See License.txt for details.
