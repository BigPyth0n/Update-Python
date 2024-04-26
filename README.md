# Update-Python

lsb_release -a

No LSB modules are available.
Distributor ID: Ubuntu
Description:    Ubuntu 24.04 LTS
Release:        24.04
Codename:       noble


apt update -y && apt upgrade -y
sudo add-apt-repository ppa:deadsnakes/ppa
apt update -y && apt upgrade -y
sudo apt install python3.12
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.12 1
python3 -V
sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev

sudo apt install python3-pip
pip3 --version
pip3 install virtualenv
python3 -m pip install virtualenv

برای فشرده کردن و اکسترکت پوشه

tar -czvf archive.tar.gz CryptoMehran

tar -xvf CryptoMehran_07-02-1403-2.tar.gz



#What is TA-LIB?

TA-Lib is widely used by trading software developers requiring to perform technical analysis of financial market data.

1 Installation

1.1 Download
wget http://prdownloads.sourceforge.net/ta-lib/ta-lib-0.4.0-src.tar.gz
tar -xzf ta-lib-0.4.0-src.tar.gz
cd ta-lib/
 
1.2 Install TA-LIB
If the next command fails, then gcc is missing, install it by doing “apt-get install build-essential”)
sudo ./configure
sudo make
sudo make install
 
1.3 Install TA-LIB Python Wrapper
Install TA-Lib Python Wrapper via pip (or pip3):
pip install ta-lib

