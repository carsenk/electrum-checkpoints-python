getcheckpoints.py
======================

A Python script to generate a checkpoints.json for Electrum with a cryptocurrency daemon

Uses the JSON RPC commands `getblockhash` and `getblock`

Usage:

``` python getcheckpoints.py <rpcusername> <rpcpassword> <rpcport> ```

It runs locally with a coin daemon. Electrum syncs checkpoint blocks 2015, 2015 + 2016, 2015 + 2016*2

======================

By Carsen Klock for Denarius (D)