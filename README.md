VnStat.js
=========

This is functional fork of VnStat.js (https://github.com/nicolargo/vnstat.js) - a simple Web interface for the VnStat utility.



Installation
------------
1) Install the VnStat and VnStati utility.

Example on Ubuntu 14.04:

	$ sudo apt-get install vnstat vnstati

2) Install the Node.js 

	$ curl -sL https://deb.nodesource.com/setup | sudo bash -
	$ sudo apt-get install -y nodejs

3) Download the VnStat.js node

	$ cd ~
	$ git clone git://github.com/FeroVolar/vnstat.js.git

Run the VnStat.js node
----------------------

Run the node:

	$ cd ~/vnstat.js
	$ node ./vnstat.js

On the console, the URL of the VnStat.js is displayed.
Use a HTML5 compatible Web browser.

![](http://i62.tinypic.com/155t0kl.png)

Informations
------------

By default, the node listen on the TCP port 8887, do not forget to open your firewall if necessary.
You can customized the web design by editing the css/style.css file.

VnStat.js use vnstat and vnstati softwares. You can edit the path using the lib/request.js file:

	var cmd_vnstat = '/usr/bin/vnstat';
	var cmd_vnstati = '/usr/bin/vnstati -c 5';

