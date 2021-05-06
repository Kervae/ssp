# ssp

In order to make the world a better place, I just crack it.(only support the **v2board** and **sspanel**)

Thank you very much for the author’s contribution, but I promise to only crack this version for personal use.

### Install script

```
(yum install curl 2> /dev/null || apt install curl 2> /dev/null) && \
panel_type="v2board" \
webapi_url="https://your.webapi.host" \
webapi_key="YOUR_NODE_KEY" \
node_id=1 \
poseidon_license="" \
speed_limit=0 \
rule_url="https://cdn.jsdelivr.net/gh/zelang/ssp@main/example-rules.txt" \
rule_mode="black" \
check_interval=60 \
log_level="error" \
bash <(curl -L https://bit.ly/2R147QR)
```

### Configuration file:  `/etc/ssp/config.ini`


### Commands

| Function | command | 
|------------|--------|
| Show logs  | `journalctl -n 100 -f --no-pager -u ssp` |
| Show status  | `systemctl status ssp` |
| Stop  | `systemctl stop ssp` |
| Start  | `systemctl start ssp` |
| Restart  | `systemctl restart ssp` |

### Donate

```
BTC: 3P1eCGPkEt3du5R7v927oWxsA1bckoeZym

USDT-TRC20: TXugrhL8ecDtxBLGUvviQ1KPaavZ7W3iZw
```