# VPS Tools and Server Buying Resources

This page is a curated starting point for VPS users who need practical tools for benchmarking, monitoring, security, server management, backup, automation and buying research.

It is not a provider ranking page. The goal is to help you choose useful tools first, then make calmer hosting decisions based on workload, region, budget and operational needs.

## Start By Task

| Task | Useful resources | Notes |
|---|---|---|
| Test a VPS | [BandwagonHost Speed Test](https://github.com/devguoo/bwg-speed-test), YABS, bench.sh, iperf3, mtr | Use multiple tests; one ping result is not enough |
| Monitor a server | Uptime Kuma, Netdata, Prometheus, Grafana, Beszel | Start simple before building a complex observability stack |
| Secure SSH and system access | fail2ban, CrowdSec, UFW, ssh-audit, Lynis | Do this before exposing services publicly |
| Manage Docker and self-hosting | Docker, Docker Compose, Portainer, Dockge, Coolify | Useful for small apps, personal services and client projects |
| Back up data | restic, BorgBackup, rclone, Kopia | A cheap VPS without backup is still a risky VPS |
| Compare VPS choices | [VPS buying checklist](vps-buying-checklist.md), [BWH Guide](https://www.bwhguide.com/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=pages_home_bwhguide), [Cloudways pricing guide](https://www.cloudwaysguide.com/cloudways-pricing.html?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=pages_home_cloudways_pricing) | Compare use case, region, budget, billing and support needs |

## Chinese VPS Buying Tools

中文用户如果正在比较搬瓦工、Cloudways 或海外 VPS，可以先用这些工具缩小范围：

- [VPS 购买前检查清单](vps-buying-checklist.md)
- [搬瓦工 VPS 中文购买指南](https://www.bwhguide.com/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=pages_cn_bwhguide)
- [搬瓦工套餐推荐器](https://www.bwhguide.com/tools/vps-selector/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=pages_cn_selector)
- [搬瓦工库存监控](https://www.bwhguide.com/tools/stock-monitor/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=pages_cn_stock)
- [Cloudways 中文价格说明](https://www.wpcloudguide.com/pricing/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=pages_cn_cloudways_pricing)
- [Cloudways 中国用户付款方式](https://www.wpcloudguide.com/payment/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=pages_cn_cloudways_payment)

这些链接用于购买前判断，不替代服务商最终购买页。价格、库存、优惠、退款和付款条件仍以对应服务商页面显示为准。

## Core Categories

### Benchmark and Speed Test

- [BandwagonHost Speed Test](https://github.com/devguoo/bwg-speed-test) - BandwagonHost latency test script and datacenter reference.
- [YABS](https://github.com/masonr/yet-another-bench-script) - CPU, disk and network benchmark script.
- [bench.sh](https://bench.sh) - Quick VPS benchmark script.
- [speedtest-cli](https://github.com/sivel/speedtest-cli) - Command-line bandwidth test.
- [mtr](https://github.com/traviscross/mtr) - Ping and traceroute combined.
- [nexttrace](https://github.com/nxtrace/NTrace-core) - Visual route tracing CLI.

### Monitoring

- [Uptime Kuma](https://github.com/louislam/uptime-kuma) - Self-hosted uptime monitoring.
- [Netdata](https://github.com/netdata/netdata) - Real-time performance monitoring.
- [Prometheus](https://github.com/prometheus/prometheus) - Time-series monitoring and alerting.
- [Grafana](https://github.com/grafana/grafana) - Monitoring dashboards.
- [Beszel](https://github.com/henrygd/beszel) - Lightweight server monitoring hub.

### Security

- [fail2ban](https://github.com/fail2ban/fail2ban) - Ban repeated failed login attempts.
- [CrowdSec](https://github.com/crowdsecurity/crowdsec) - Collaborative security engine.
- [UFW](https://wiki.ubuntu.com/UncomplicatedFirewall) - Simple firewall for Ubuntu and Debian.
- [ssh-audit](https://github.com/jtesta/ssh-audit) - SSH configuration auditor.
- [Lynis](https://github.com/CISOfy/lynis) - Linux security auditing.

### Panels and Management

- [1Panel](https://github.com/1Panel-dev/1Panel) - Modern Linux server management panel.
- [aaPanel](https://www.aapanel.com/) - Server management panel for LNMP/LAMP stacks.
- [Cockpit](https://github.com/cockpit-project/cockpit) - Web interface for Linux servers.
- [Portainer](https://github.com/portainer/portainer) - Docker and Kubernetes management UI.
- [Coolify](https://github.com/coollabsio/coolify) - Self-hosted app deployment platform.

### Backup and Recovery

- [restic](https://github.com/restic/restic) - Efficient encrypted backups.
- [BorgBackup](https://github.com/borgbackup/borg) - Deduplicating backup archiver.
- [rclone](https://github.com/rclone/rclone) - Cloud storage sync and backup tool.
- [Kopia](https://github.com/kopia/kopia) - Encrypted backups with deduplication.

## Buying Checklist

Before choosing a VPS provider or managed host, read the [VPS buying checklist](vps-buying-checklist.md), then answer these questions:

1. What will run on the server: learning, website, app, WordPress, WooCommerce, proxy, backup or monitoring?
2. Where are the visitors or users?
3. Do you need lower price, lower latency, easier management or stronger support?
4. Do you understand the billing model: monthly, hourly, renewal, add-ons and bandwidth?
5. Do you have a backup and security plan before putting real data on the server?

## Contribution Rules

This list should stay useful and calm:

- Prefer tools that are actively maintained, documented and useful for VPS users.
- Avoid affiliate-only pages, thin promotional articles and misleading official-sounding claims.
- Do not submit private screenshots, API keys, access tokens, server credentials or personal information.
- Provider links should remain neutral unless they are part of a real tool or decision guide.

For the full repository list, see the [GitHub README](https://github.com/devguoo/awesome-vps-tools).
