# PingPoint NOC

A self-hosted network operations centre, built by [Nacho Pola](https://github.com/NachoPola16) and [Martín Longares](https://github.com/martin05mlg).

It collects **SNMP, syslog and IPFIX** (plus Proxmox VE, Linux hosts, DNS and ICMP), stores everything in SQLite, shows it in a web dashboard with an interactive topology map, and alerts to ntfy, Discord, Slack, Telegram, webhook or email. No Grafana, no Zabbix.

## Repository

| Project | What it is |
|---|---|
| [**pingpoint-noc**](https://github.com/pingpoint-noc/pingpoint-noc) | The NOC itself: collectors, API, alert engine and web dashboard. Python, MIT licensed. |

Issues and pull requests are welcome; see `CONTRIBUTING.md` in the repository.
