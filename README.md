### What to do?

1. Setup KMD & GAME (importing privkey and make sure funds are there) like you did for Season 3 [help guide if needed](https://docs.komodoplatform.com/notary/setup-Komodo-Notary-Node.html)
2. (Re)Start KMD & GAME with `-pubkey` arg
3. Install [`nanomsg`](https://docs.komodoplatform.com/notary/setup-Komodo-Notary-Node.html#install-nanomsg)
4. Clone dPoW repo https://github.com/himu007/dPoW
5. Create `pubkey.txt` file inside `~/dPoW/iguana/` dir
6. Create `wp_7779` file inside `~/dPoW/iguana/` dir and make it executable
7. Issue the following commands
```
cd ~/dPoW/iguana
./m_notary_build
./m_notary_3rdparty
```
8. Split KMD with 10000 satoshis
9. Split GAME with 100000 satoshis

Some Info:

```
Minsig - 13
Iguana port to open - 17776
```
