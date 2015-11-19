# pve
---
## Python Virtualenv Manager

[![Join the chat at https://gitter.im/royxue/pve](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/royxue/pve?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

![](pve.gif)

Prototype made in Facebook Seattle Hackathon, idea inspired by [n](https://github.com/tj/n)

## Installation
Install python virtualenv by pip first.

One easy way is 

    	npm install -g pve

Or use "ln" to create symlink in /usr/local/bin, and chmod 755 to pve file.

## Usage
	 Usage: pve [COMMAND] [args]
     
     Commands:
    		pve                            Output Virtualenvs Installed
    		pve new <anme>                 Create New Virtualenvs <name>
    		pve <name>                     Activate to Vitualenv <name>
    		pve rm <anme>                  Remove the Given Vitualenv <name>
    		pve -l, list                   List all installed Virtualenvs

     Options:
   		 	-h, --help      Display help information
   		 	
## License
The MIT License (MIT)