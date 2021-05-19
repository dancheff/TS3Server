# Auto Install the Linux TeamSpeak 3 Server on Debian / Ubuntu / Centos

## **What this script does:**

✔ Creates a new user to run the TeamSpeak 3 Server

✔ Downloads and installs the server

✔ Creates a systemd service 

✔ Starts the server

## **How to use:**

## Download the script
```bash
git clone https://github.com/dancheff/TS3Server.git
cd TS3Server
```

## Change the user variables if necessary

```bash
nano ts3server.sh
```

## Make the script executable
                                       
```bash
chmod a+x ts3server.sh
```

## Run the script

```bash
./ts3server.sh
```

## To start, stop, restart, or check the status of the ts3server use

```bash
systemctl {start|stop|restart|status} ts3server
```

## Bugs & Issues
Please feel free to report any bugs or issues to us, email to: valentin@dancheff.com or [open issue](http://github.com/dancheff/TS3Server/issues) on Github.
