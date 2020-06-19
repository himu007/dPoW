### What to do?

1. Setup KMD & GAME (importing privkey and make sure funds are there) like you did for Season 3 [help guide if needed](https://docs.komodoplatform.com/notary/setup-Komodo-Notary-Node.html)
2. (Re)Start KMD & GAME with `-pubkey` arg
3. Install [`nanomsg`](https://docs.komodoplatform.com/notary/setup-Komodo-Notary-Node.html#install-nanomsg)
4. Clone dPoW repo https://github.com/himu007/dPoW
5. Create `pubkey.txt` file inside `~/dPoW/iguana/` dir
6. Create `wp_7779` file inside `~/dPoW/iguana/` dir and make it executable
7. Open port `17776` in your firewall for iguana
8. Issue the following commands
```
cd ~/dPoW/iguana
./m_notary_build
./m_notary_3rdparty
```
9. Split KMD with 10000 satoshis
10. Split GAME with 100000 satoshis

#### Bootstrap Links
- [KMD](https://eu.bootstrap.dexstats.info/KMD-bootstrap.tar.gz)
- [GAME](https://eu.bootstrap.dexstats.info/GAME-bootstrap.tar.gz)
#### How to use Bootstrap?
Make sure both KMD & GAME daemon are stopped before using bootstrap. Once finished with the commands below, restart daemons with `-pubkey` arg as usual.  
**KMD**  
```
cd ~/.komodo
wget https://eu.bootstrap.dexstats.info/KMD-bootstrap.tar.gz
tar xvf KMD-bootstrap.tar.gz
```
**GAME**  
```
cd ~/.gamecredits
wget https://eu.bootstrap.dexstats.info/GAME-bootstrap.tar.gz
tar xvf GAME-bootstrap.tar.gz
```
