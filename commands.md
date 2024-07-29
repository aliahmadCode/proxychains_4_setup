

```

sudo systemctl start tor
systemctl status tor
proxychains4 curl http://check.torproject.org
proxychains4 curl https://api.ipify.org
proxychains4 firefox

# adding command [SocksPort 9050]
sudo nvim /etc/tor/torrc 

sudo curl --socks5 127.0.0.1:9050 http://check.torproject.org
ps aux | grep tor
sudo apt update
sudo apt install tor proxychains
```
