# Node.js setup
Node.js v12.x cause this is the LTS version right now.

# Using Ubuntu
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install -y nodejs


```sudo apt remove nodejs```
This command will remove the package and retain the configuration files. These may be of use to you if you intend to install the package again at a later point. If you don’t want to save the configuration files for later use, then run the following:


```sudo apt purge nodejs```
This will uninstall the package and remove the configuration files associated with it.

