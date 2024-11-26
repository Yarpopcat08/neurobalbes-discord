# Neurobalbes-discord
Eventually, Neurobalbes. A discord bot that generates it's messages based on yours

---

### How to install & run the bot
First of all, install node.js from their official website using their package managers. I tried using **vnm** and **fnm** on **Ubuntu 22.04** and **Debian 12** and I can gurantee that these are working configurations.
After that, check that both node.js and npm are installed.

> **Important note!** Node.js needs to be of version **v20.16.0** otherwise you will get a ton of errors later when installing dependencies 

After installing everything, you can clone or download this repo, and in the directory of the project enter command `npm install` 

Next, if you are on Debian/Ubuntu run this command to installed required build-dependencies: `sudo apt-get install build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev pkg-config` and then run `npm rebuild canvas`
When all dependencies are installed, please configure the bot in config.json, then run `node reg.js` to update slash commands, when they are finished updating run the bot via `node shard.js`
Congrats, the bot should be running now!


## How to install & run on Android?

Why... okay.

For this you need termux with proot-distro installed and configured. No tutorial or explanation on how to use it will be provided here as there is enough information about it on the Internet. After installing the OS you need to enter these commands in the terminal (using **Ubuntu** as an example):
`apt intsall nodejs` and `apt install npm` Then go to Nodejs website to install the required version `20.16.0` then copy the command and paste it into the terminal. If everything works, then typing the command `node` in the terminal you will get this:

> root@localhost:~# node
 Welcome to Node.js v20.16.0.
 Type ".help" for more information.

The bot has proven to work on such setup, however we are not sure about the efficency and cannot recommend running the bot like that. 
