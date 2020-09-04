# TS3Server
**Auto Install the Linux TeamSpeak 3 Server on Debian / Ubuntu / Centos**

**What this script does:**

*Creates a new user to run the TeamSpeak 3 Server*

*Downloads and installs the server*

*Creates a systemd service*

**Starts the server**

**How to use:**

**Download or copy the script and paste it into a new file**

wget 

**Change the user variables if necessary**

nano ts3server.sh
**Make the script executable**
                                       
chmod a+x ts3server.sh

**Run the script**

sudo .ts3server.sh

**To start, stop, restart, or check the status of the ts3-server use**

sudo systemctl {start|stop|restart|status} ts3server 
