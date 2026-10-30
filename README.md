<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="brand/wordmark-dark.svg">
    <img src="brand/wordmark.svg" alt="Open Company" width="320">
  </picture>
</p>

# opencompany.run

[中文](README.zh-CN.md)

Source for [opencompany.run](https://opencompany.run), the template directory for [Open Company](https://open-company.org) (`open-company/v0`)—an open standard for multi-agent collaboration.

The page dynamically loads [`catalog.json`](https://raw.githubusercontent.com/munk-sh/open-company/main/catalog.json) from [`munk-sh/open-company`](https://github.com/munk-sh/open-company) (with a local `./catalog.json` fallback) and provides one-click `munk://company/import?url=...` deep-link import into [Munk AI](https://munk.sh).

## Preview locally

Serve this directory:

```bash
python3 -m http.server 4321
```

Open <http://127.0.0.1:4321>. The header switches between 中文 and English.
