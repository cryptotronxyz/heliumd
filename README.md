# Helium Daemon
### Bash installer for Helium Daemon on Ubuntu 16.04 LTS x64

#### This shell script comes with 3 cronjobs: 
1. Make sure the daemon is always running: `makerun.sh`
2. Make sure the daemon is never stuck: `checkdaemon.sh`
4. Clear the log file every other day: `clearlog.sh`

1. A custom port for SSH, as firewall will be enabled and only the custom port will be allowed for SSH

#### Login to your vps as root, download the heliumd-install.sh file and then run it:
```
wget https://rawgit.com/cryptotronxyz/heliumd/master/heliumd-install.sh
bash ./heliumd-install.sh
```
#### Your daemon should be setup now!
