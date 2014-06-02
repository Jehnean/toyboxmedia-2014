ToyBox Media site.
 
Development Environment
=======================

(pre-vagrant)

For Mac OSX:

* Install XAMPP
* Click "Manage Servers".
* Select Apache Web Server and click "Configure"
* Click "Open Conf File" and confirm the warning message.
* Find lines labelled "DocumentRoot" and "Directory" which are set to "/Applications/XAMPP/xamppfiles".  Change each to
  the path to your clone of this git repo. For example:

	DocumentRoot "/Users/dkern/development/toyboxmedia"
	Directory "/Users/dkern/development/toyboxmedia"

* Save the configuration file
* Click the "Restart" button for the Apache Web Server to reload the configuration

For Windows:

* Install WAMP

For Linux:

* Do some sudo apt-get's.
