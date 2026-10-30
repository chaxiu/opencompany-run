<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="brand/wordmark-dark.svg">
    <img src="brand/wordmark.svg" alt="Open Company" width="320">
  </picture>
</p>

# opencompany.run

[English](README.md)

[opencompany.run](https://opencompany.run) 的站点源码。收录遵循 [Open Company 规范](https://open-company.org)（`open-company/v0`，多 Agent 协作的开放标准）的团队模板。

页面优先从官方模板库 [`munk-sh/open-company`](https://github.com/munk-sh/open-company) 实时拉取 [`catalog.json`](https://raw.githubusercontent.com/munk-sh/open-company/main/catalog.json)（带本地 `./catalog.json` 兜底），支持通过 `munk://company/import?url=...` 深度链接一键唤起 [Munk AI](https://munk.sh) 桌面端导入运行。

## 本地预览

在本目录起一个静态文件服务：

```bash
python3 -m http.server 4321
```

打开 <http://127.0.0.1:4321>。页头可切换中文 / English。
