# Awesome VPS Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of useful tools, scripts, and resources for VPS users — speed testing, monitoring, benchmarking, server management, and more.

> ⭐ Star this repo to bookmark it — new tools added regularly.

[![GitHub stars](https://img.shields.io/github/stars/devguoo/awesome-vps-tools?style=social)](https://github.com/devguoo/awesome-vps-tools)
[![Last Commit](https://img.shields.io/github/last-commit/devguoo/awesome-vps-tools)](https://github.com/devguoo/awesome-vps-tools/commits/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> 💡 Looking for a reliable VPS? I personally use [BandwagonHost CN2 GIA-E](https://bwh81.net/aff.php?aff=77647) — low latency from Asia, great uptime. Use code `BWHCGLUKKB` for 6.78% off.

---

## Contents

- [Speed Test & Latency](#speed-test--latency)
- [Benchmarking](#benchmarking)
- [Monitoring](#monitoring)
- [Server Setup & Hardening](#server-setup--hardening)
- [Networking & DNS](#networking--dns)
- [Automation & Deployment](#automation--deployment)
- [Control Panels](#control-panels)
- [Cloud Providers](#cloud-providers)
- [Learning Resources](#learning-resources)
- [Communities](#communities)

---

## Speed Test & Latency

- [bwg-speed-test](https://github.com/devguoo/bwg-speed-test) — One-click speed test for all BandwagonHost data centers (CN2 GIA, ping, bandwidth).
- [speedtest-cli](https://github.com/sivel/speedtest-cli) — Command line interface for testing internet bandwidth using speedtest.net.
- [LibreSpeed](https://github.com/librespeed/speedtest) — Self-hosted speed test. No Flash, no Java, no WebSocket.
- [mtr](https://github.com/traviscross/mtr) — Network diagnostic tool combining ping and traceroute.
- [nexttrace](https://github.com/nxtrace/NTrace-core) — Visual route tracing CLI tool with real-time map.
- [BestTrace](https://www.ipip.net/product/client.html) — Route tracing tool with visual map, great for China routes.
- [ping.pe](https://ping.pe) — Online ping tool from 30+ global locations.
- [itdog.cn](https://www.itdog.cn) — Ping and route test from China ISPs (Telecom/Unicom/Mobile).

## Benchmarking

- [YABS](https://github.com/masonr/yet-another-bench-script) — Yet Another Bench Script — CPU, disk, and network benchmarks in one go.
- [bench.sh](https://bench.sh) — Quick VPS benchmark script (I/O, speed, system info).
- [Geekbench](https://www.geekbench.com/) — Cross-platform CPU benchmark with online result database.
- [sysbench](https://github.com/akopytov/sysbench) — Scriptable multi-threaded benchmark tool for CPU, memory, I/O.
- [fio](https://github.com/axboe/fio) — Flexible I/O tester for disk performance.
- [iperf3](https://github.com/esnet/iperf) — Network throughput measurement tool.
- [UnixBench](https://github.com/kdlucas/byte-unixbench) — Classic Unix system benchmark suite.
- [VPSBenchmarks](https://www.vpsbenchmarks.com/) — Community-driven VPS performance comparison database.

## Monitoring

- [Uptime Kuma](https://github.com/louislam/uptime-kuma) — Self-hosted monitoring tool with beautiful UI. Supports HTTP, TCP, ping, DNS.
- [Netdata](https://github.com/netdata/netdata) — Real-time performance monitoring with zero configuration.
- [Prometheus](https://github.com/prometheus/prometheus) — Monitoring system with time series database and alerting.
- [Grafana](https://github.com/grafana/grafana) — Visualization and analytics platform for monitoring data.
- [Zabbix](https://github.com/zabbix/zabbix) — Enterprise-class monitoring solution.
- [htop](https://github.com/htop-dev/htop) — Interactive process viewer for Unix systems.
- [btop](https://github.com/aristocratos/btop) — Resource monitor with beautiful TUI (CPU, memory, disk, network).
- [Glances](https://github.com/nicolargo/glances) — Cross-platform system monitoring tool written in Python.

## Server Setup & Hardening

- [linux-server-init](https://github.com/devguoo/linux-server-init) — One-click Linux server initialization (SSH hardening, firewall, Docker, Nginx). *(Coming soon)*
- [fail2ban](https://github.com/fail2ban/fail2ban) — Ban IPs with too many failed login attempts.
- [UFW](https://wiki.ubuntu.com/UncomplicatedFirewall) — Uncomplicated Firewall for Ubuntu/Debian.
- [CrowdSec](https://github.com/crowdsecurity/crowdsec) — Collaborative security engine — like fail2ban on steroids.
- [Lynis](https://github.com/CISOfy/lynis) — Security auditing tool for Linux/macOS/Unix.
- [ssh-audit](https://github.com/jtesta/ssh-audit) — SSH server & client configuration auditor.
- [Docker](https://github.com/docker/docker-ce) — Container platform for deploying applications.
- [Caddy](https://github.com/caddyserver/caddy) — Web server with automatic HTTPS.
- [Nginx Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager) — Easy reverse proxy with Let's Encrypt SSL.

## Networking & DNS

- [WireGuard](https://github.com/WireGuard/wireguard-linux) — Fast, modern, secure VPN tunnel.
- [Cloudflare WARP](https://1.1.1.1/) — Free VPN and DNS resolver by Cloudflare.
- [Pi-hole](https://github.com/pi-hole/pi-hole) — Network-wide ad blocking via DNS.
- [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) — Network-wide ad and tracker blocking DNS server.
- [CoreDNS](https://github.com/coredns/coredns) — DNS server written in Go, plugin-based.
- [dig](https://linux.die.net/man/1/dig) — DNS lookup utility (part of bind-utils).
- [doggo](https://github.com/mr-karan/doggo) — Modern DNS client with colorful output.

## Automation & Deployment

- [Ansible](https://github.com/ansible/ansible) — Agentless IT automation platform.
- [Terraform](https://github.com/hashicorp/terraform) — Infrastructure as Code for cloud resources.
- [Pulumi](https://github.com/pulumi/pulumi) — Infrastructure as Code using real programming languages.
- [Kamal](https://github.com/basecamp/kamal) — Deploy web apps anywhere with zero downtime.
- [Coolify](https://github.com/coollabsio/coolify) — Self-hosted Heroku/Netlify/Vercel alternative.

## Control Panels

- [aaPanel](https://www.aapanel.com/) — Free server management panel (web-based, supports LNMP/LAMP).
- [1Panel](https://github.com/1Panel-dev/1Panel) — Modern Linux server management panel.
- [Webmin](https://github.com/webmin/webmin) — Web-based system administration interface.
- [CyberPanel](https://github.com/usmannasir/cyberpanel) — Web hosting control panel powered by OpenLiteSpeed.
- [HestiaCP](https://github.com/hestiacp/hestiacp) — Lightweight web server control panel.

## Cloud Providers

| Provider | Starting Price | Highlights | Link |
|----------|---------------|------------|------|
| **BandwagonHost** | $49.99/yr | CN2 GIA-E, great for Asia, 11 data centers | [Visit](https://bwh81.net/aff.php?aff=77647) |
| **Vultr** | $2.50/mo | 32+ locations, hourly billing, up to $300 free credit | [Visit](https://www.vultr.com/?ref=8985760) |
| DigitalOcean | $4/mo | Simple, developer-friendly | [Visit](https://www.digitalocean.com/) |
| Linode (Akamai) | $5/mo | Reliable, good network | [Visit](https://www.linode.com/) |
| Hetzner | €3.79/mo | Best value in Europe | [Visit](https://www.hetzner.com/) |
| Oracle Cloud | Free tier | Always-free ARM instances | [Visit](https://www.oracle.com/cloud/free/) |
| AWS Lightsail | $3.50/mo | AWS simplified | [Visit](https://aws.amazon.com/lightsail/) |

> More detailed VPS comparisons and buying guides at [bwhhost.com](https://www.bwhhost.com) (BandwagonHost) and [vultrinfo.com](https://www.vultrinfo.com) (Vultr).

## Learning Resources

- [Linux Journey](https://linuxjourney.com/) — Free interactive Linux learning.
- [DigitalOcean Tutorials](https://www.digitalocean.com/community/tutorials) — High-quality server tutorials.
- [Linuxize](https://linuxize.com/) — Practical Linux tutorials and tips.
- [How to Set Up a VPS](https://github.com/devguoo/vps-buying-guide) — Complete VPS buying and setup guide. *(Coming soon)*

## Related Projects

- 🚀 [bwg-speed-test](https://github.com/devguoo/bwg-speed-test) — 搬瓦工多机房一键测速工具

---

## Communities

- [LowEndTalk](https://lowendtalk.com/) — VPS deals and discussions.
- [NodeSeek](https://www.nodeseek.com/) — Chinese VPS community.
- [V2EX](https://www.v2ex.com/go/vps) — Chinese tech community, VPS section.
- [r/selfhosted](https://www.reddit.com/r/selfhosted/) — Self-hosting community on Reddit.
- [r/homelab](https://www.reddit.com/r/homelab/) — Home server enthusiasts.
- [ServerFault](https://serverfault.com/) — Q&A for system administrators.

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

If you find this list useful, please give it a ⭐ — it helps others discover it too.

## License

[MIT](LICENSE)
