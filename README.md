# Clash / Mihomo routing rules

This repository contains the current routing rules exported from a Clash/Mihomo subscription template. It intentionally excludes DNS settings, proxy groups and nodes, subscription URLs, account credentials, and private keys.

## Files

- `rules.yaml` — standalone `rules:` section for review or reuse.

## Note about Tencent Cloud ranges

The current rule set sends every CIDR listed in the source below to `DIRECT`. These are general Tencent Cloud IP ranges, not WeChat-only ranges; unrelated traffic to those addresses will also bypass the proxy.

Source list: [Tencent Cloud server IP ranges](https://www.jiajingyu.com/3729.html), page marked updated 2025-04-24. The list is copied as supplied and may become outdated; review it before relying on it for security-sensitive routing.
