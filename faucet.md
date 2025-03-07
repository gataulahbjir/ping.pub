# Guild for faucet service

## Submit You Config

```json
{
    "chain_name": "cosmos",
    // string array ["url1", "url2"] is deprecated.
    // must be [{"address": union10v9cs5y4uw9r6j7l5ya8mpfu57q3pxp4as600q "", "provider": ""}]
    "api": [
        {
            "address": "https://cosmos.api.ping.pub", 
            "provider": "Ping"
        }
    ], 
    "rpc": [
        {
            "address": "https://cosmos.api.ping.pub:443", 
            "provider": "Ping"
        }
    ],
    // ... ...
    "faucet": {
        "amount": "5000000uatom,50000000uside",
        "ip_limit": "1",
        "address_limit": "10",
        "fees": "1000uatom"
    }
}
```

## Fund the faucet account

Visit your faucet page on [testnet.ping.pub](https://testnet.ping.pub)

find the address and send some tokens to the address.
