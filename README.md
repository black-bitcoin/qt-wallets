# qt-wallets
Linux, Windows and MAC Daemon and wallet files

# Please this dependencies for run QT wallet and or daemon on Ubuntu 16.04 system 
sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils git cmake libboost-all-dev

sudo apt-get install software-properties-common

sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt-get update

sudo apt-get install libdb4.8-dev libdb4.8++-dev

sudo apt-get install libqt4-dev libminiupnpc-dev

# Daemon and wallet config file 

# please create config file with name BlackBitCoin.conf and Put 

 rpcuser=yourusername

 rpcpassword=password
 
 server=1
 
 listen=1
 
 daemon=1
 
 staking=0 //if want disable staking
 
 torproxy=0

# Thats it...
****************************************************************************************************
# To Run Windows QT Wallet No need to install any dependencies 
Just download and open the file
****************************************************************************************************
# To Run QT on MAC --- install Deps as below
  1. Download Homebrew for MAC by going to https://brew.sh/ 
  2. Download File mac_dependencies.sh 
  3. Open Terminal and cd to/path/mac_dependencies.sh
  4. chmod +x mac_dependencies.sh (run this command in terminal)
  5. sudo bash mac_dependencies.sh (final Command)
  6. Run QT wallet file .dmg
  

