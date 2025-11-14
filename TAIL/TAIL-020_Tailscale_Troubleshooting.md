# TAIL-020 Tailscale Troubleshooting

```yaml
id: TAIL-020
title: Tailscale Troubleshooting
category: tail
status: draft
owner: Johnny Leuthard
last_verified: 
notes: 
```

## Service Checks
Status  
```
sudo systemctl status tailscaled
```

Restart  
```
sudo systemctl restart tailscaled
```

Logs  
```
journalctl -u tailscaled --no-pager
```

## Network Checks
Peer state  
```
tailscale status
```

Connectivity  
```
ping <peer-ip>
```

NAT and relay
```
tailscale netcheck
```

## Reset
```
sudo tailscale up --reset
```
