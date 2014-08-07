autossh-ubuntu-startup-script
=============================

startup script for autossh:

1. Put the autosshtunnel script in your /etc/init.d/ directory
2. create these directories: 
	mkdir /etc/autossh
	mkdir /var/lock/subsys
3. Put the config file in /etc/autossh and change the settings to yours.


####usage
/etc/init.d/autosshtunnnel -h
Usage: /etc/init.d/autosshtunnnel {start|stop|restart|status} {config names...}

####start
/etc/init.d/autosshtunnnel start your_config

####stop
/etc/init.d/autosshtunnnel stop your_config

####status
/etc/init.d/autosshtunnnel status your_config
