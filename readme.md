##shadowsocks-manager

```
    $ ssserver --manager-address /var/run/shadowsocks-manager.sock -c /etc/shadowsocks.json -d start
    $ go build -o ss-manager main.go && ./ss-manager -h
```