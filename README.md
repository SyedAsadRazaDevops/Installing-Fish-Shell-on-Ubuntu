# Installing-Fish-Shell-on-Ubuntu
All linux / ubuntu servers deployed on cloud are configured to use the Bash shell by default. Fish is an alternative for Bash that provides the following additional features:


- Command suggestion.
- A more intuitive command system.
- An overall more modern shell.

This tutorial will teach you how to install Fish on Ubuntu Server.

# Installation
# Step 1: Downloading Fish
You can install Fish with apt-get:

```
apt-get install fish
```
# Step 2: Entering Fish
You can now enter the Fish shell simply by typing:
```
fish
```
# Step 3: Setting Fish as your default shell
You can set Fish as your default shell instead of Bash:
```
chsh -s /usr/bin/fish
```

#Step 4: Creating a config file
In order to be able to change the properties of the Fish shell, we first need to create a config file.
```
mkdir -p ~/.config/fish
vim ~/.config/fish/config.fish
```

# Step 6: Switching back to Bash
If you would like to use Bash again, simply type:
```
bash
```
If you want to permanently use Bash as your default shell, type:
```
chsh -s /bin/bash
```


DONE THANK YOU!

Visit: https://fishshell.com/docs/current/tutorial.html
