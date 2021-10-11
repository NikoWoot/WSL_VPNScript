<h3 align="center">WSL VPN Script.</h3>
<p align="center">Refresh WSL container with host DNS settings.</p>

---

## Requirements

- WSL 2
- Powershell

## Install

- Copy force_dns_refresh to your user home.
- Add this to your .bashrc
```
if [ -f ~/force_dns_refresh.sh ]; then
    . ~/force_dns_refresh.sh
fi
```

### Use this script

When you enable or disable your VPN:

```bash
force_dns_refresh
```