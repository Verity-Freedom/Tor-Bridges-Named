# Tor-Bridges-Namer

Why am I doing this?
```
Each Tor bridge has a different uptime and bandwidth. To use Tor most effectively, you need to take the best bridges.

According to the Kerckhoffs's principle, the encryption system should remain secure, even if all its details are known. Therefore, the naming of the Tor bridges does not pose any threats.

The original Tor Bridges Collector stores a huge number of irretrievably deceased bridges and does not double-check their condition. By naming the bridge, I confirm its operability at the time of naming.
```

Types of pluggable transport:
```
WebTunnel bridges are a censor resistant proxies that try to imitate HTTPS traffic, based on HTTPT research.

Obfs4 bridges makes Tor traffic look random, and also prevents censors from finding bridges by Internet scanning.

Snowflake bridges are improvement upon Flashproxy. It sends your traffic through WebRTC, a peer-to-peer protocol with built-in NAT punching.

Vanilla bridges are unobfuscated bridges. Very similar to usual relays, but not listed publicly like them.
```
