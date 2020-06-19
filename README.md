### What to do?

1. Setup KMD & GAME (importing privkey and make sure funds are there) like you did for Season 3
2. (Re)Start KMD & GAME with `-pubkey` arg
2. Clone dPoW repo https://github.com/himu007/dPoW
3. Create `pubkey.txt` file inside `~/dPoW/iguana/` dir
4. Create `wp_7779` file inside `~/dPoW/iguana/` dir and make it executable
5. Issue the following commands
```
cd ~/dPoW/iguana
./m_notary_build
./m_notary_3rdparty
```
6. Split KMD with 10000 satoshis
7. Split GAME with 100000 satoshis

