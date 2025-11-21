## <img width="48" height="48" alt="image" src="https://github.com/user-attachments/assets/06763573-810e-4314-963e-7a0bc792f482" /> Adguard DNSproxy-1-click
A simple DNS proxy server that supports all existing DNS protocols including DNS-over-TLS, DNS-over-HTTPS, DNSCrypt, and DNS-over-QUIC. Moreover, it can work as a DNS-over-HTTPS, DNS-over-TLS or DNS-over-QUIC server.
#### 💠It performs the following tasks:
- Install DNSproxy
- Install systemd service
- Install DoH config w Cloudflare DNS, cache
- Other config and option https://github.com/AdguardTeam/dnsproxy
- Rewrite service config if you need
💠 Copy, paste and run
```
wget "https://raw.githubusercontent.com/Onair-santa/Adguard-DNSproxy-1-click/main/dnsproxy.sh" -O dnsproxy.sh && chmod +x dnsproxy.sh && bash dnsproxy.sh
```
💠Start, stop, restart.
- systemctl start dnsproxy
- systemctl stop dnsproxy
- systemctl restart dnsproxy

#### 💠 Thanks
https://github.com/AdguardTeam/dnsproxy
