Employee Launchpad built off a Linktree clone. 

To deploy changes, log into fkportainer.convergentdx.com, open the container that is running the caddy_launchpad, and console in using /bin/sh.

Type /var/www/gitlaunchpad.sh and press enter.

This .sh script will syncronize the local webserver to the github repository, thereby making the revisions added to github live on the launchpad. 