# HTML Sandbox


## Table of Contents
* Getting Started
* Using
* Contribution Guidelines
* Known Bugs
* FAQ
* License


## Getting Started

There are submodules, so clone the repo using

`$ git clone --recursive ...`

Before you can use Grunt, you need to run

`$ npm install`

`$ sudo npm install -g grunt-cli`

`$ npm install grunt-responsive-images --save`


## Using

### Setup

1. Set permissions  
`$ ./setperms.sh`

2. Allow HTTP.  
`$ sudo ufw allow http`

3. Serve.  
`$ python3 -m http.server 80`

### Takedown

1. Stop serving with ctrl+c.

2. Deny HTTP.  
`$ sudo ufw deny http`

3. Confirm denial.  
`$ sudo ufw status`


## Contribution Guidelines
. . .


## Known Bugs
. . .


## FAQ
. . .


## License

Unlicense, but check submodule terms.
