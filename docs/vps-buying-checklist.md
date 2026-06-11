# VPS Buying Checklist / VPS 购买前检查清单

This checklist is for developers, site owners and self-hosting users who are comparing VPS providers, managed WordPress hosting, or cloud servers. It helps you decide what to check before paying, instead of choosing only by the lowest visible price.

中文用户可以从[中文 VPS 购买与选型入口](zh-cn/)开始，也可以直接阅读：[VPS 购买前检查清单（中文版）](zh-cn/vps-buying-checklist.md)。本页保留为英文版购买前核对表。

## Quick Decision

| Your situation | Better starting point | Why |
|---|---|---|
| You want a self-managed VPS | Compare route, region, bandwidth, snapshots and your Linux skill level | You manage security, backups, updates and troubleshooting yourself |
| You are choosing BandwagonHost / 搬瓦工 | [BWH plan selector](https://www.bwhguide.com/tools/vps-selector/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_bwh_selector) and [stock monitor](https://www.bwhguide.com/tools/stock-monitor/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_bwh_stock) | Route, datacenter and stock matter more than a single low price |
| You are choosing Cloudways for WordPress | [Cloudways pricing guide](https://www.cloudwaysguide.com/cloudways-pricing.html?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_cloudways_pricing) | Managed WordPress cost depends on route, provider, region, add-ons and checkout amount |
| You prefer Chinese Cloudways guidance | [Cloudways 中文价格说明](https://www.wpcloudguide.com/pricing/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_wpcloudguide_pricing) | 中文用户可以先看价格、付款和建站流程 |
| You only need tools | Return to the [VPS tools directory](README.md) | Benchmarking, monitoring, security, panels and backups come first |

## 1. Workload

Before comparing providers, define what will actually run on the server:

- Linux learning or temporary testing;
- static site or small blog;
- WordPress, WooCommerce or client site;
- app backend, database or API;
- monitoring, backup or automation node;
- high-traffic production workload.

A cheap VPS can be enough for learning, but a production site needs a backup plan, monitoring and security basics.

## 2. Visitor Region

Choose the region for your visitors, not only for yourself.

| Visitor location | What to compare |
|---|---|
| Chinese users | route quality, datacenter choice, latency, packet loss and stock |
| Asia users | Hong Kong, Japan, Singapore and nearby regional routes |
| US/EU users | region close to the main audience, provider network and support |
| Global users | CDN, DNS, origin location and failover plan |

If route quality matters, run more than one test and compare results at different times. One ping result is not enough.

## 3. Budget and Billing

Do not compare only the first visible monthly price. Check:

- monthly vs hourly billing;
- renewal price;
- bandwidth and transfer limits;
- snapshot and backup cost;
- add-ons such as email, DNS, CDN or security;
- taxes, credits and payment method issues;
- refund policy and cancellation timing.

For Cloudways users, use the [Cloudways checkout price checklist](https://devguoo.github.io/cloudways-pricing/en/checkout-price-checklist.html?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_cloudways_checkout) before testing coupons or launching a server.

## 4. Management Difficulty

Self-managed VPS and managed hosting solve different problems.

| Option | You handle | Better for |
|---|---|---|
| Self-managed VPS | SSH, firewall, updates, backups, monitoring, web stack | Technical users, learning, flexible projects |
| Managed WordPress host | Less server maintenance, more platform limits and monthly cost | WordPress users who prefer speed of setup and support |
| Hybrid platform like Cloudways | Server route/provider decisions plus managed dashboard | WordPress or agency projects that need more control than fully managed hosting |

If you do not want to manage Linux security and backups, the cheapest unmanaged VPS may not be the real cheapest option.

## 5. Backup and Security

Before putting real data on a server, prepare:

- SSH key login;
- firewall rules;
- update policy;
- uptime monitoring;
- off-server backup;
- restore test;
- safe credential storage rules.

Useful tools are listed on the [VPS tools directory](README.md), especially monitoring, security and backup sections.

## 6. Provider-Specific Notes

### BandwagonHost / 搬瓦工

For BandwagonHost, do not choose only by storage size. Check:

- series: CN2 GIA-E, Hong Kong, Tokyo, Osaka, Singapore, KVM PROMO, ECOMMERCE SLA;
- current stock;
- available datacenter;
- route and latency from your target users;
- billing cycle and plan upgrade path.

Useful Chinese entry points:

- [搬瓦工套餐推荐器](https://www.bwhguide.com/tools/vps-selector/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_bwh_related_selector)
- [搬瓦工库存监控](https://www.bwhguide.com/tools/stock-monitor/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_bwh_related_stock)
- [搬瓦工套餐和机房选择](https://www.bwhguide.com/plans/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_bwh_related_plans)

### Cloudways

For Cloudways, separate pricing and hosting route first:

- Flexible vs Autonomous;
- provider, server size and region;
- WordPress, WooCommerce, agency or higher-traffic use case;
- add-ons and billing behavior;
- coupon validity at the official checkout.

Useful entry points:

- [Cloudways pricing guide](https://www.cloudwaysguide.com/cloudways-pricing.html?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_cloudways_related_pricing)
- [Cloudways coupon and checkout notes](https://www.cloudwaysguide.com/cloudways-coupon.html?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_cloudways_related_coupon)
- [Cloudways 中文价格说明](https://www.wpcloudguide.com/pricing/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_cloudways_related_cn_pricing)

## 中文快速核对

购买 VPS 前至少问自己：

1. 是学习、建站、WordPress、外贸站、备用节点，还是正式业务？
2. 用户主要在哪个地区？
3. 我能不能自己处理 SSH、安全、备份和故障？
4. 是想省钱，还是想省管理时间？
5. 价格、库存、付款周期和退款条件是否都看清楚了？
6. 有没有提前准备替代方案？

如果你还不确定，可以先从[搬瓦工套餐推荐器](https://www.bwhguide.com/tools/vps-selector/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_cn_selector)或[Cloudways 中文价格说明](https://www.wpcloudguide.com/pricing/?utm_source=github&utm_medium=pages&utm_campaign=awesome_vps_tools&utm_content=buying_checklist_cn_cloudways)开始。

## What This Page Avoids

- No raw affiliate links.
- No private dashboard screenshots.
- No claim that one provider is best for everyone.
- No outdated fixed price table.
- No official-sounding wording for independent guides.

Final price, stock, route availability, promotion and refund policy should always be checked on the relevant provider page before purchase.
