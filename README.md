# hanya untuk linux

Tambahkan alamat ip anda di
https://github.com/frmdeveloper/vpn/blob/frm/permission/ip
```
Ini adalah sc colongan, gw mau ngilangin izin IP tapi males.
```



- Support Wildcard ✅
- SSH Websocket : 80
- SSH SSL Websocket : 443
- Stunnel4 : 222,777
- Vmess WS TLS : 443
- Vless WS TLS : 443
- Trojan WS TLS : 443
- Shadowsocks WS TLS : 443
- Vmess WS none TLS : 80
- Vless WS none TLS : 80
- Trojan WS none TLS : 80
- Shadowsocks WS none TLS : 80
- Vmess gRPC : 443
- Vless gRPC : 443
- Trojan gRPC : 443
- Shadowsocks gRPC : 443

___
**INSTALL** (wajib masuk root)
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils curl unzip && wget https://raw.githubusercontent.com/frmdeveloper/vpn/frm/setup.sh && chmod +x setup.sh && sed -i -e 's/\r$//' setup.sh && ./setup.sh
