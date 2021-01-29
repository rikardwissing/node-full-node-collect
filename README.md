# node-full-node-collect

Help us collect information about the Myriad network

## Usage
`./run PORT`

Data will be saved in ./data/client-ip.json

## Client usage
`curl -d "$(myriadcoin-cli -rpcuser=RPCUSER -rpcpassword=RPCPASSWORD -rpcport=RPCPORT getpeerinfo)" -H "Content-Type: application/json" -X POST http://ip-to-server`

Thank you
