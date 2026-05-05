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

## Configure Git on VM
```
sudo apt-get update
sudo apt-get install git
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
ssh-keygen -t ed25519 -C "your.email@example.com"
cat ~/.ssh/id_ed25519.pub
ssh -T git@github.com      // test connection
```
```
// Inside ee282_s25_pa1/
git init
git remote add origin git@github.com:kguerns/EE282_Computer_Architecture.git
git pull origin main --allow-unrelated-histories
```
