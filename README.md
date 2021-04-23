# ssp

### 系统直接安装

```
(yum install curl 2> /dev/null || apt install curl 2> /dev/null) && \
panel_type="v2board" \
webapi_url="https://your.webapi.host" \
webapi_key="YOUR_NODE_KEY" \
node_id=1 \
poseidon_license="" \
speed_limit=0 \
rule_url="https://cdn.jsdelivr.net/gh/dy6324/ssp@main/example-rules.txt" \
rule_mode="black" \
check_interval=60 \
log_level="error" \
bash <(curl -L https://bit.ly/3etWrhV)
```

### 配置文件 `/etc/ssp/config.ini`


### 操作命令

| Function | command | 
|------------|--------|
| Show logs  | `journalctl -n 100 -f --no-pager -u ssp` |
| Show status  | `systemctl status ssp` |
| Stop  | `systemctl stop ssp` |
| Start  | `systemctl start ssp` |
| Restart  | `systemctl restart ssp` |