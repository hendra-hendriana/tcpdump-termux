# tcpdump-termux

### Setup
apt update && apt upgrade \
pkg install tsu \
apt install wget \
wget https://www.androidtcpdump.com/download/4.9.2/tcpdump && chmod +x tcpdump

### Usage
tsu \
./tcpdump -h 

### Example
./tcpdump -i rmnet_data0
