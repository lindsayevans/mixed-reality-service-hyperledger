# Mixed Reality Service Hyperledger
Backend for Mixed Reality Service based on Hyperledger v0.6


## Run local Hyperledger instance
Runs a local Hyperledger instance in a Docker container for chaincode testing

```
chmod +x scripts/hyperledger/run.sh
scripts/hyperledger/run.sh
```

## Chaincode development

TODO: Go env setup - https://github.com/IBM-Blockchain/learn-chaincode/blob/master/docs/setup.md

Edit `src/chaincode.go`

To test chaincode builds correctly:
```
go build -o ./chaincode-mrs ./src
```

