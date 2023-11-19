# PIVOting
![_e2ab6875-7348-48e6-afa0-08ac82e2e94b](https://github.com/szybnev/pivoting/assets/32132485/68b731fd-7ae1-4841-93cd-9f0ba2412737)


# Protocols
- Socks
- HTTP(S)
- SSH
- DNS
- ICMP
- RDP
- SMB
- VPN like
- Multi-protocol

## Socks
[proxychains](https://github.com/haad/proxychains) - ProxyChains is a UNIX program, that hooks network-related libc functions in dynamically linked programs via a preloaded DLL and redirects the connections through SOCKS4a/5 or HTTP proxies.<br>
[proxychains-ng](https://github.com/rofl0r/proxychains-ng) - proxychains ng (new generation) - a preloader which hooks calls to sockets in dynamically linked programs and redirects it through one or more socks/http proxies. continuation of the unmaintained proxychains project. the sf.net page is currently not updated, use releases from github release page instead.<br>
[resocks](https://github.com/RedTeamPentesting/resocks) - resocks is a reverse/back-connect SOCKS5 proxy tunnel that can be used to route traffic through a system that can't be directly accessed (e.g. due to NAT).<br>
[SSF](https://github.com/securesocketfunneling/ssf) - Secure Socket Funneling - Network tool and toolkit - TCP and UDP port forwarding, SOCKS proxy, remote shell, standalone and cross platform.

## HTTP(S)
[chisel](https://github.com/jpillora/chisel) - Chisel is a fast TCP/UDP tunnel, transported over HTTP, secured via SSH. Single executable including both client and server. Written in Go (golang). Chisel is mainly useful for passing through firewalls, though it can also be used to provide a secure endpoint into your network.


## SSH
[sshuttle](https://github.com/sshuttle/sshuttle) - Transparent proxy server that works as a poor man's VPN. Forwards over ssh. Doesn't require admin. Works with Linux and MacOS. Supports DNS tunneling.

## VPN Like
[ligolo-ng](https://github.com/nicocha30/ligolo-ng) - An advanced, yet simple, tunneling/pivoting tool that uses a TUN interface.

## Multi-protocol
[graftcp](https://github.com/hmgle/graftcp) - graftcp can redirect the TCP connection made by the given program [application, script, shell, etc.] to SOCKS5 or HTTP proxy.<br>
[gost](https://github.com/ginuerzh/gost) - GO Simple Tunnel, a simple tunnel written in golang.<br>
[3proxy](https://github.com/3proxy/3proxy) - tiny free proxy server.

# Exfiltration
## NTP
[ntpescape](https://github.com/evallen/ntpescape) - A reasonably stealthy NTP data exfiltration client.
