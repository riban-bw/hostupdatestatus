# hostupdatestatus
Bash scripts to report the update status of Debian / Ubuntu hosts on the LAN

# Description
This project is a set of bash scripts that run on Ubuntu and Debian hosts.

Run hostupdatestatus_server on the server that will act as the main server, serving up the web interface.

Run hostupdatestatus_client on each host on the network. This should be called peridically, e.g. once per day via a cron job.

The client checks its update status and sends this info to the server which subsequently updates its web page. The web page is hosted by a simple web server.

# Credits
Brian Walton authored the scripts.
Sortable table from Stuart Langridge (http://www.kryogenix.org/code/browser/sorttable).

