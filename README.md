# JSON Resume Registry Server

[![Join the chat at https://gitter.im/jsonresume/public](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jsonresume/public?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build Status](https://travis-ci.org/jsonresume/registry-server.svg?branch=master)](https://travis-ci.org/jsonresume/registry-server) [![Dependency Status](https://david-dm.org/jsonresume/registry-server.svg)](https://david-dm.org/jsonresume/registry-server) [![devDependency Status](https://david-dm.org/jsonresume/registry-server/dev-status.svg)](https://david-dm.org/jsonresume/registry-server#info=devDependencies)
﻿[![Issue Stats](http://www.issuestats.com/github/jsonresume/registry-server/badge/pr?style=flat)](http://www.issuestats.com/github/jsonresume/registry-server) [![Issue Stats](http://www.issuestats.com/github/jsonresume/registry-server/badge/issue?style=flat)](http://www.issuestats.com/github/jsonresume/registry-server)



## Installation

Requirements: MongoDB, Redis

1. Clone the repository
1. `npm install`
1. `git submodule update --init --recursive --depth 1`
1. `mongo 127.0.0.1:27017/jsonresume --eval "db.resumes.insert({})"`
1. `MONGOHQ_URL=mongodb://127.0.0.1:27017/jsonresume node server.js`

*Alternatively:*

Requirements: Vagrant, Virtualbox

1. Clone the repository
1. `vagrant up`
1. `vagrant ssh`
1. `node server.js`

## Testing

To run the tests, simply run:

    npm test

## Documentation
For additional documentation please see the [Wiki page](https://github.com/jsonresume/resume-docs/wiki/Registry-Server).

## License

Available under [the MIT license](http://mths.be/mit).

