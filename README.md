# EE282_Computer_Architecture

## VM Setup Commands
```
sudo apt-get -y update && sudo apt-get -y install wget python-is-python3
wget https://web.stanford.edu/class/ee282/ee282_s26_pa1.tar.gz -O- | tar -xz
cd ee282_s25_pa1
./gce_setup.sh
cd pa1/
./zsim.sh -a blackscholes -b wide -c 4
```
