# Bash Shell Auto Install Titan Node L2 - Cassini Testnet on Ubuntu 22.04
- Install (version v0.1.19)
```
curl -O https://raw.githubusercontent.com/rosewinlet/titan-install/main/install.sh && chmod u+x install.sh && ./install.sh
```
- Show Info & Config node
```
titan-edge config show && titan-edge info
```
- If errors, delete folder `.titanedge` and reinstall
```
systemctl stop titand.service && rm -rf /root/.titanedge && rm -rf /usr/local/titan
```
------------
- Ref Titan Dashboard: https://test1.titannet.io/intiveRegister?code=CtKlIe
- Telegram Offical: https://t.me/titannet_dao
- Hidden Gems Community (HGC): https://t.me/HGCdotGG
