# Node.js setup
Node.js v12.x cause this is the LTS version right now.

**On Ubuntu**
```
1. curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
2. sudo apt-get install -y nodejs
```

```sudo apt remove nodejs```</br>
This command will remove the package and retain the configuration files. These may be of use to you if you intend to install the package again at a later point. If you don’t want to save the configuration files for later use, then run the following:


```sudo apt purge nodejs```</br>
This will uninstall the package and remove the configuration files associated with it.

**Get a scaffold web app ready using npx**</br>
You can run the application generator with the npx command (available in Node.js 8.2.0).
```$ npx express-generator```
