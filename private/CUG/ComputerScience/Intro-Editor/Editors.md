# Editors

## nano



## ee



## vim



## sublime text

```bash
# The apt repository contains packages for both x86-64 and arm64.
# Install the GPG key:

wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -

# Ensure apt is set up to work with https sources:

sudo apt-get install apt-transport-https

# Select the channel to use:
# Stable
echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list

# Dev
echo "deb https://download.sublimetext.com/ apt/dev/" | sudo tee /etc/apt/sources.list.d/sublime-text.list

# Update apt sources and install Sublime Text

sudo apt-get update
sudo apt-get install sublime-text

```



## typora

```bash
# or run:
# sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys BA300B7755AFCFAE

wget -qO - https://typora.io/linux/public-key.asc | sudo apt-key add -

# Ensure apt is set up to work with https sources:

sudo apt-get install apt-transport-https

# add Typora's repository
# sudo add-apt-repository 'deb https://typora.io/linux ./'

echo "deb https://typora.io/linux ./" | sudo tee /etc/apt/sources.list.d/typora.list

# install typora

sudo apt-get update
sudo apt-get install typora

```



## markdown





## emacs

