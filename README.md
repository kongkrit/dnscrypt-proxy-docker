# dnscrypt-proxy with Docker

Secure, private DNS using dnscrypt-proxy and Docker with both DoT and DoH upstreams.

## Features
- Cloudflare, Google, and Quad9 (no filter) DoH and DoT
- DNSSEC validation, no logging, no filtering
- Works on most platforms (x86, ARM, etc.)
- Healthcheck with `dnsprobe`
- Auto-updated resolver list

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
