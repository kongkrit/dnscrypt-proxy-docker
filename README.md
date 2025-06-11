# dnscrypt-proxy with Docker

Secure, private DNS using dnscrypt-proxy and Docker with both DoT and DoH upstreams.

## Features
- Cloudflare, Google, and Quad9 (unfiltered) via DoT/DoH
- DNSSEC validation
- No logging, no filtering
- Auto-updating resolver list

## Quick Start

```bash
git clone https://github.com/kongkrit/dnscrypt-proxy-docker.git
cd dnscrypt-proxy-docker
docker-compose up -d
```

## Test DNS

```bash
dig @127.0.0.1 example.com
```
