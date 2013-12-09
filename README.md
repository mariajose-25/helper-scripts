helper-scripts
==============

Several scripts to help a Unix system administrator or desktop power user
Quick setup:
* Clone the repository (recommended location /opt/helper-scripts)
* Go to the cloned directory
	$ cd /opt/helper-scripts/bin
* Make sure all scripts are executable
	$ chmod +x *.sh
* Generate scripts for basic desktop functions
	$ ./populate-basic-desktop-commands.sh
* Generate setup for your user environement
	$ ./setup-helper-scripts.sh 
	# START - helper-scripts stuff
	HS_HOME=/opt/helper-scripts
	PATH=$PATH:$HS_HOME/bin:$HS_HOME/sbin
	export PATH HS_HOME
	$HS_HOME/bin/backup-historial.sh > $HOME/.historial-1000.log & 
	# END - helper-scripts stuff
* Add above lines to your $HOME/.bashrc
* Restart your user session
* Enjoy your "endless" bash history  and some other usefull scripts :)

Some more info  (spanish reading) about backup-historial.sh 
	http://afeltes.blogspot.com/2012/03/historial-de-historiales-de-lineas-de.html

