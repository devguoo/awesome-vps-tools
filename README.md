# Awesome VPS Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome tools, scripts, and resources for VPS management — benchmarking, monitoring, security, containers, panels, and more.

⭐ Star this repo to bookmark it — new tools added regularly.

---

## Contents

- [Benchmark & Speed Test](#-benchmark--speed-test)
- [Monitoring](#-monitoring)
- [Security](#️-security)
- [Container & Orchestration](#-container--orchestration)
- [Web Server & Reverse Proxy](#-web-server--reverse-proxy)
- [Panel & Management](#-panel--management)
- [Backup & Snapshot](#-backup--snapshot)
- [Automation](#-automation)
- [DNS & CDN](#-dns--cdn)
- [Networking & VPN](#-networking--vpn)
- [OS & Distro](#️-os--distro)
- [Learning Resources](#-learning-resources)
- [VPS Providers](#️-vps-providers)
- [Communities](#-communities)

---

## 🔧 Benchmark & Speed Test

- [YABS](https://github.com/masonr/yet-another-bench-script) - Yet Another Bench Script — CPU, disk, and network benchmarks in one go.
- [bench.sh](https://bench.sh) - Quick VPS benchmark script covering I/O, speed, and system info.
- [speedtest-cli](https://github.com/sivel/speedtest-cli) - Command-line interface for testing internet bandwidth using speedtest.net.
- [LibreSpeed](https://github.com/librespeed/speedtest) - Self-hosted speed test with no Flash, Java, or WebSocket required.
- [nench](https://github.com/n-st/nench) - VPS benchmark script based on bench.sh with more detailed I/O tests.
- [Geekbench](https://www.geekbench.com/) - Cross-platform CPU benchmark with an online result database.
- [sysbench](https://github.com/akopytov/sysbench) - Scriptable multi-threaded benchmark tool for CPU, memory, and I/O.
- [fio](https://github.com/axboe/fio) - Flexible I/O tester for measuring disk performance.
- [iperf3](https://github.com/esnet/iperf) - Network throughput measurement tool supporting TCP and UDP.
- [UnixBench](https://github.com/kdlucas/byte-unixbench) - Classic Unix system benchmark suite.
- [Trippy](https://github.com/fujiapple852/trippy) - Network diagnostic tool combining traceroute and ping with a rich TUI.
- [mtr](https://github.com/traviscross/mtr) - Network diagnostic tool combining ping and traceroute.
- [nexttrace](https://github.com/nxtrace/NTrace-core) - Visual route tracing CLI tool with real-time map.
- [ping.pe](https://ping.pe) - Online ping tool from 30+ global locations.
- [VPSBenchmarks](https://www.vpsbenchmarks.com/) - Community-driven VPS performance comparison database.

## 📊 Monitoring

- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - Self-hosted monitoring tool with a beautiful UI supporting HTTP, TCP, ping, and DNS.
- [Netdata](https://github.com/netdata/netdata) - Real-time performance monitoring with zero configuration.
- [Prometheus](https://github.com/prometheus/prometheus) - Monitoring system with a time series database and alerting.
- [Grafana](https://github.com/grafana/grafana) - Visualization and analytics platform for monitoring data.
- [Zabbix](https://github.com/zabbix/zabbix) - Enterprise-class open-source monitoring solution.
- [Beszel](https://github.com/henrygd/beszel) - Lightweight server monitoring hub with Docker stats, historical data, and alerts.
- [OneUptime](https://github.com/OneUptime/oneuptime) - Open-source observability platform for monitoring, status pages, and incident management.
- [htop](https://github.com/htop-dev/htop) - Interactive process viewer for Unix systems.
- [btop](https://github.com/aristocratos/btop) - Resource monitor with a beautiful TUI showing CPU, memory, disk, and network.
- [Glances](https://github.com/nicolargo/glances) - Cross-platform system monitoring tool written in Python.
- [Ward](https://github.com/Rudolf-Barbu/Ward) - Minimal and beautiful server monitoring dashboard.
- [Nagios](https://github.com/NagiosEnterprises/nagioscore) - Industry-standard IT infrastructure monitoring.
- [Checkmk](https://github.com/Checkmk/checkmk) - Monitoring platform for servers, networks, and cloud infrastructure.
- [Gatus](https://github.com/TwiN/gatus) - Developer-oriented health dashboard with configurable alerts and conditions for endpoints.
- [Scrutiny](https://github.com/AnalogJ/scrutiny) - Hard drive S.M.A.R.T. monitoring with a web UI and historical trends.

## 🛡️ Security

- [fail2ban](https://github.com/fail2ban/fail2ban) - Ban IPs with too many failed login attempts.
- [CrowdSec](https://github.com/crowdsecurity/crowdsec) - Collaborative security engine with community-driven blocklists.
- [UFW](https://wiki.ubuntu.com/UncomplicatedFirewall) - Uncomplicated Firewall for Ubuntu/Debian.
- [Lynis](https://github.com/CISOfy/lynis) - Security auditing tool for Linux, macOS, and Unix.
- [ssh-audit](https://github.com/jtesta/ssh-audit) - SSH server and client configuration auditor.
- [rkhunter](https://rkhunter.sourceforge.net/) - Rootkit detection tool for POSIX systems.
- [chkrootkit](https://github.com/Magentron/chkrootkit) - Tool to locally check for signs of a rootkit.
- [OpenSCAP](https://github.com/OpenSCAP/openscap) - Security compliance and vulnerability scanning framework.
- [OSSEC](https://github.com/ossec/ossec-hids) - Host-based intrusion detection system.
- [Wazuh](https://github.com/wazuh/wazuh) - Open-source security platform for threat detection, compliance, and incident response.
- [Trivy](https://github.com/aquasecurity/trivy) - Comprehensive vulnerability scanner for containers, filesystems, and git repositories.

## 🐳 Container & Orchestration

- [Docker](https://github.com/moby/moby) - Container platform for building and deploying applications.
- [Portainer](https://github.com/portainer/portainer) - Lightweight management UI for Docker, Swarm, and Kubernetes.
- [K3s](https://github.com/k3s-io/k3s) - Lightweight Kubernetes distribution for IoT and edge computing.
- [CasaOS](https://github.com/IceWhaleTech/CasaOS) - Simple personal cloud system built around Docker.
- [Podman](https://github.com/containers/podman) - Daemonless container engine compatible with Docker CLI.
- [Docker Compose](https://github.com/docker/compose) - Define and run multi-container applications with YAML.
- [Traefik](https://github.com/traefik/traefik) - Cloud-native application proxy and ingress controller.
- [Watchtower](https://github.com/containrrr/watchtower) - Automatically update running Docker containers.
- [ctop](https://github.com/bcicen/ctop) - Top-like interface for container metrics.
- [Dockge](https://github.com/louislam/dockge) - Self-hosted Docker Compose stack manager with a reactive web UI.

## 🌐 Web Server & Reverse Proxy

- [Nginx](https://github.com/nginx/nginx) - High-performance HTTP server and reverse proxy.
- [Caddy](https://github.com/caddyserver/caddy) - Web server with automatic HTTPS via Let's Encrypt.
- [Apache HTTP Server](https://github.com/apache/httpd) - The world's most widely used web server.
- [Nginx Proxy Manager](https://github.com/NginxProxyManager/nginx-proxy-manager) - Easy reverse proxy management with free SSL.
- [OpenResty](https://github.com/openresty/openresty) - High-performance web platform based on Nginx and LuaJIT.
- [HAProxy](https://github.com/haproxy/haproxy) - Reliable, high-performance TCP/HTTP load balancer.
- [Varnish](https://github.com/varnishcache/varnish-cache) - High-performance HTTP accelerator and caching reverse proxy.

## 📁 Panel & Management

- [1Panel](https://github.com/1Panel-dev/1Panel) - Modern Linux server management panel with a clean UI.
- [aaPanel](https://www.aapanel.com/) - Free server management panel supporting LNMP/LAMP stacks.
- [Webmin](https://github.com/webmin/webmin) - Web-based system administration interface for Unix.
- [Cockpit](https://github.com/cockpit-project/cockpit) - Web-based graphical interface for Linux servers.
- [CyberPanel](https://github.com/usmannasir/cyberpanel) - Web hosting control panel powered by OpenLiteSpeed.
- [HestiaCP](https://github.com/hestiacp/hestiacp) - Lightweight and open-source web server control panel.
- [Coolify](https://github.com/coollabsio/coolify) - Self-hosted Heroku/Netlify/Vercel alternative.
- [Termix](https://github.com/Termix-SSH/Termix) - Web-based server management platform with SSH terminal, tunneling, and file editing.

## 💾 Backup & Snapshot

- [restic](https://github.com/restic/restic) - Fast, secure, and efficient backup program.
- [BorgBackup](https://github.com/borgbackup/borg) - Deduplicating archiver with compression and encryption.
- [rclone](https://github.com/rclone/rclone) - Rsync for cloud storage supporting S3, Dropbox, Google Drive, and 40+ backends.
- [Kopia](https://github.com/kopia/kopia) - Fast encrypted backups with deduplication and cloud support.
- [Duplicati](https://github.com/duplicati/duplicati) - Free backup client with web UI supporting encrypted incremental backups.
- [duplicity](https://duplicity.gitlab.io/) - Encrypted bandwidth-efficient backup using the rsync algorithm.
- [rsnapshot](https://github.com/rsnapshot/rsnapshot) - Filesystem snapshot utility based on rsync.
- [Velero](https://github.com/vmware-tanzu/velero) - Back up and migrate Kubernetes resources and persistent volumes.

## 🔄 Automation

- [Ansible](https://github.com/ansible/ansible) - Agentless IT automation platform for configuration management and deployment.
- [Terraform](https://github.com/hashicorp/terraform) - Infrastructure as Code for provisioning cloud resources.
- [Pulumi](https://github.com/pulumi/pulumi) - Infrastructure as Code using real programming languages.
- [cloud-init](https://github.com/canonical/cloud-init) - Industry-standard tool for cross-platform cloud instance initialization.
- [Kamal](https://github.com/basecamp/kamal) - Deploy web apps anywhere with zero downtime.
- [linux-server-init](https://github.com/devguoo/linux-server-init) - One-click Linux server initialization covering SSH hardening, firewall, Docker, and Nginx setup.
- [StackScript](https://www.linode.com/docs/products/tools/stackscripts/) - Linode's custom provisioning scripts for automated server setup.
- [Fabric](https://github.com/fabric/fabric) - Simple Pythonic remote execution and deployment tool.

## 📈 DNS & CDN

- [Cloudflare](https://www.cloudflare.com/) - Global CDN, DNS, DDoS protection, and web application firewall.
- [Pi-hole](https://github.com/pi-hole/pi-hole) - Network-wide ad blocking via DNS.
- [AdGuard Home](https://github.com/AdguardTeam/AdGuardHome) - Network-wide ad and tracker blocking DNS server.
- [CoreDNS](https://github.com/coredns/coredns) - Plugin-based DNS server written in Go.
- [PowerDNS](https://github.com/PowerDNS/pdns) - Authoritative and recursive DNS server with broad backend support.
- [doggo](https://github.com/mr-karan/doggo) - Modern DNS client with colorful output.
- [KeyCDN Tools](https://tools.keycdn.com/) - Free online tools for DNS lookup, HTTP headers, and performance testing.

## 🔗 Networking & VPN

- [WireGuard](https://github.com/WireGuard/wireguard-linux) - Fast, modern, and secure VPN tunnel.
- [Tailscale](https://github.com/tailscale/tailscale) - Zero-config mesh VPN built on WireGuard.
- [Headscale](https://github.com/juanfont/headscale) - Self-hosted implementation of the Tailscale control server.
- [Netmaker](https://github.com/gravitl/netmaker) - Platform for creating fast and secure virtual networks with WireGuard.
- [frp](https://github.com/fatedier/frp) - Fast reverse proxy to expose a local server behind a NAT or firewall.
- [Cloudflare Tunnel](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/) - Secure tunnel to connect your origin server to Cloudflare without a public IP.

## 🖥️ OS & Distro

- [Ubuntu Server](https://ubuntu.com/server) - Most popular Linux server distribution with long-term support.
- [Debian](https://www.debian.org/) - Rock-solid, community-driven Linux distribution.
- [AlmaLinux](https://almalinux.org/) - Free enterprise Linux distribution, CentOS replacement.
- [Rocky Linux](https://rockylinux.org/) - Enterprise Linux built to be 100% bug-for-bug compatible with RHEL.
- [Fedora Server](https://fedoraproject.org/server/) - Cutting-edge features in a stable server platform.
- [Alpine Linux](https://www.alpinelinux.org/) - Security-oriented, lightweight Linux distribution popular for containers.
- [Arch Linux](https://archlinux.org/) - Lightweight and flexible rolling-release distribution.
- [NixOS](https://nixos.org/) - Linux distribution with a unique declarative configuration model.

## 📚 Learning Resources

- [Linux Journey](https://linuxjourney.com/) - Free interactive Linux learning for beginners.
- [DigitalOcean Tutorials](https://www.digitalocean.com/community/tutorials) - High-quality, community-reviewed server tutorials.
- [Linuxize](https://linuxize.com/) - Practical Linux tutorials and tips.
- [linuxcommand.org](https://linuxcommand.org/) - Learn the Linux command line with free online lessons.
- [The Linux Documentation Project](https://tldp.org/) - Collection of Linux guides, HOWTOs, and FAQs.
- [Servers for Hackers](https://serversforhackers.com/) - Server administration tutorials for developers.
- [Self-Hosted Podcast](https://selfhosted.show/) - Podcast about self-hosting, home automation, and servers.
- [Awesome Sysadmin](https://github.com/awesome-foss/awesome-sysadmin) - Curated list of open-source sysadmin resources, tools, and software.

## 🏷️ VPS Providers

- [BandwagonHost](https://www.bwhhost.com) - Budget-friendly VPS with CN2 GIA-E for low-latency Asia routes.
- [Vultr](https://www.vultrinfo.com) - Cloud compute with 32+ global locations and hourly billing.
- [DigitalOcean](https://www.digitaloceanpro.com) - Developer-friendly cloud platform with simple pricing.
- [Cloudways](https://www.cloudwaysguide.com) - Managed hosting on top of DigitalOcean, AWS, and GCP.
- [Kinsta](https://www.kinstainfo.com) - Premium managed WordPress and application hosting on GCP.
- [Linode (Akamai)](https://www.linode.com/) - Reliable cloud hosting with a strong developer community.
- [Hetzner](https://www.hetzner.com/) - Best value cloud hosting in Europe with powerful hardware.
- [Oracle Cloud](https://www.oracle.com/cloud/free/) - Generous always-free tier including ARM instances.
- [AWS Lightsail](https://aws.amazon.com/lightsail/) - Simplified AWS experience for small projects.
- [Google Cloud](https://cloud.google.com/) - Enterprise cloud with a free tier and global network.
- [Azure](https://azure.microsoft.com/) - Microsoft's cloud platform with comprehensive services.
- [OVHcloud](https://www.ovhcloud.com/) - European cloud provider with competitive pricing and bare metal servers.
- [Scaleway](https://www.scaleway.com/) - European cloud with innovative offerings and a generous free tier.
- [Contabo](https://contabo.com/) - High-resource VPS at aggressive prices.
- [RackNerd](https://www.racknerd.com/) - Budget VPS provider with frequent promotional deals.
- [HostHatch](https://hosthatch.com/) - NVMe-powered VPS across multiple global locations.
- [BuyVM](https://buyvm.net/) - Affordable VPS with DDoS protection and block storage.

### VPS Review & Comparison

- [LowEndBox](https://lowendbox.com/) - Budget VPS deals and provider reviews.
- [ServerHunter](https://www.serverhunter.com/) - VPS price comparison engine across 50+ providers.
- [VPS Best](https://www.vps-best.com) - VPS recommendations and buying guides.

## 💬 Communities

- [LowEndTalk](https://lowendtalk.com/) - The largest VPS deals and discussion forum.
- [r/selfhosted](https://www.reddit.com/r/selfhosted/) - Self-hosting community on Reddit.
- [r/homelab](https://www.reddit.com/r/homelab/) - Home server enthusiasts community.
- [ServerFault](https://serverfault.com/) - Q&A site for system and network administrators.
- [NodeSeek](https://www.nodeseek.com/) - Chinese-language VPS community and marketplace.

---

## Contributing

Contributions welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [devguoo](https://github.com/devguoo) has waived all copyright and related or neighboring rights to this work.
2026-04-11
