# Relayer Namada <=======> Osmosis     

Moniker: SolanaFlipper

Public key: tpknam1qpkf4ev2zu7d8c2r0jr4q06tttjm625463t9c2lvkv7uhx6cp0ruwp6p8xs

Transperen address:  tnam1qp7ag54ty634g3p2dj45w382t838v3zhhqygt2u9

Osmosis address: osmo1vkv6m383rngzzzxtf0teljrmcl4297xlr7p79v

**osmo-test-5:
channel id - 6270**

**namada:
channel id - 809**


### Create channel Namada <> Osmosis

```sql
SUCCESS Channel {
    ordering: Unordered,
    a_side: ChannelSide {
        chain: BaseChainHandle {
            chain_id: ChainId {
                id: "shielded-expedition.88f17d1d14",
                version: 0,
            },
            runtime_sender: Sender { .. },
        },
        client_id: ClientId(
            "07-tendermint-2674",
        ),
        connection_id: ConnectionId(
            "connection-1307",
        ),
        port_id: PortId(
            "transfer",
        ),
        channel_id: Some(
            ChannelId(
                "channel-809",
            ),
        ),
        version: None,
    },
    b_side: ChannelSide {
        chain: BaseChainHandle {
            chain_id: ChainId {
                id: "osmo-test-5",
                version: 5,
            },
            runtime_sender: Sender { .. },
        },
        client_id: ClientId(
            "07-tendermint-2835",
        ),
        connection_id: ConnectionId(
            "connection-2573",
        ),
        port_id: PortId(
            "transfer",
        ),
        channel_id: Some(
            ChannelId(
                "channel-6270",
            ),
        ),
        version: None,
    },
    connection_delay: 0ns,
 SUCCESS Channel {
    ordering: Unordered,
    a_side: ChannelSide {
        chain: BaseChainHandle {
            chain_id: ChainId {
                id: "shielded-expedition.88f17d1d14",
                version: 0,
            },
            runtime_sender: Sender { .. },
        },
        client_id: ClientId(
            "07-tendermint-2674",
        ),
        connection_id: ConnectionId(
            "connection-1307",
        ),
        port_id: PortId(
            "transfer",
        ),
        channel_id: Some(
            ChannelId(
                "channel-809",
            ),
        ),
        version: None,
    },
    b_side: ChannelSide {
        chain: BaseChainHandle {
            chain_id: ChainId {
                id: "osmo-test-5",
                version: 5,
            },
            runtime_sender: Sender { .. },
        },
        client_id: ClientId(
            "07-tendermint-2835",
        ),
        connection_id: ConnectionId(
            "connection-2573",
        ),
        port_id: PortId(
            "transfer",
        ),
        channel_id: Some(
            ChannelId(
                "channel-6270",
            ),
        ),
        version: None,
    },
    connection_delay: 0ns,
	}}
```

**IBC transaction Namada - Osmosis**

 ```asp
Transaction added to mempool.
Wrapper transaction hash: 3DB1FE7BE2FEB188F784DCAA93029062208593FB9052AF1DB3B746A73FFF9D40
Inner transaction hash: 68BB314369E56CA4B17C5938D51176081EE76910B5FB403C3E5E06081AD944BB
Wrapper transaction accepted at height 120604. Used 26 gas.
Waiting for inner transaction result...
Transaction was successfully applied at height 120605. Used 6193 gas.
```


https://www.mintscan.io/osmosis-testnet/tx/681461EE2BCBD777CAF06DC26F8EBDAED772E963C83172E46100D1E2D60E387F?height=5965039
