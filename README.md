# TxShardAffinity

A basic example of achieving shard affinity for transactions for optimised performance.

Run the `TxShardAffinity.mongodb` code either in __VS Code__ (using its __MongoDB Plugin__) or in the __MongoDB Shell__ (`mongosh`).

The code assumes sthe sharded clsuter connected to has just 2 shards, which are called "shard0", "shard1". If this is not the case, then first change the value of the variable `shardNames` in the code.
