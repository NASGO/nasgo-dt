# nasgo-dt
nasgo development tools

Usage:  [options] [command]

  Options:

    -V, --version      output the version number
    -H, --host <host>  Specify the ip of nasgo node, default: 127.0.0.1 (default: 127.0.0.1)
    -P, --port <port>  Specify the port of the node, default: 9040 (default: 9040)
    -h, --help         output usage information


  Commands:

    getheight                  get block height
    getblockstatus             get block status
    getbalance [address]       get balance by address
    getaccount [address]       get account by address
    getpeers [options]         get peers
    sendmoney [options]        send money to some address
    sendasset [options]        send asset to some address
    setsecondsecret [options]  set second secret
    publishDapp [options]      publish a dapp
    createGenesis [options]    create genesis block
    deposit [options]          deposit assets to an app
    dapptransaction [options]  create a dapp transaction
