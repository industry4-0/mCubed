# mCubed
TID 2
Install Multichain by running the below commands:

wget https://www.multichain.com/download/multichain-2.0.3.tar.gz
tar -xvzf multichain-2.0.3.tar.gz
cd multichain-2.0.3

Initilize blockchainNOW4.0:
multichaind NOW4.0 -daemon

Run dashboard with the following commands:
npm install
npm start

Configure Web Explorer:
cat ~/.multichain/chain1/multichain.conf
grep rpc-port ~/.multichain/chain1/params.dat
cp config-example.txt config.txt

default.name=Default                # name to display in the web interface
default.rpchost=127.0.0.1           # IP address of MultiChain node
default.rpcport=12345               # usually default-rpc-port from params.dat
default.rpcuser=multichainrpc       # username for RPC from multichain.conf
default.rpcpassword=mnBh8aHp4mun... # password for RPC from multichain.conf

Run communication protocol:
cd gps
python3 gps.py


