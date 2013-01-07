Flotronix
=========
Flotronix is extension for Monitorix (Monitorix with Flot(javascriptRRD+Flot)).    
Monitorix is a free, open source, lightweight system monitoring tool designed to monitor as many services and system resources as possible.    
JavascriptRRD is a javascript library for reading and interpreting RRD. The javascriptRRD package provides the basic RRD reading libraries, as well as helper libraries to make displaying of RRD files easy with the Flot library.   
Flot is a Javascript plotting library for jQuery.

ScreenShot
----------
![ScreenShot](https://raw.github.com/degtyarev-dm/Flotronix/master/flotronix.png)

How to use
----------
To start use Flotronix you need copy Flotronix folder to web server (like apache), and create folder `lib` like link to folder with Monitorix rrd file.
For example:

	/var/www/
			/flotronix
			/lib -> /var/lib/monitorix

License
-------
Flotronix is free software licensed under the terms of the GNU General Public License version 2 (GPLv2).

Credits
-------
Monitorix was created by [Jordi Sanfeliu](http://www.fibranet.cat).   
JavascriptRRD is developed on [http://javascriptrrd.sourceforge.net/](http://javascriptrrd.sourceforge.net/)
Flot was started by Ole Laursen, sponsored by IOLA. Read more at the website: [http://www.flotcharts.org/](http://www.flotcharts.org/).   
Flotronix was created by [Dmitry Degtyarev](mailto:degtyarev.dm@gmail.com).