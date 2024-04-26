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

pip3 install virtualenv

برای فشرده کردن و اکسترکت پوشه

tar -czvf archive.tar.gz CryptoMehran

tar -xvf CryptoMehran_07-02-1403-2.tar.gz

برای تغییر نام یک فولدر، از دستور mv به شکل زیر استفاده کنید:


