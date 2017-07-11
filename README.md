# BITCOIN-MINE
#Code for raspberrypi for mining bitcoins efficiently

sudo apt-get update
sudo apt-get install autoconf autogen libtool uthash-dev libjansson-dev libcurl4-openssl-dev libusb-dev libncurses-dev git-core –y


cd bfgminer
./autogen.sh
./configure
make
