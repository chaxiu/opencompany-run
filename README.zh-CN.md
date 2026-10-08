<p align="center">
  <img src="brand/logo.svg" alt="Open Company" width="96">
</p>

# opencompany.run

[English](README.md)

[opencompany.run](https://opencompany.run) 的源码。这一站列出按 [Open Company 规范](https://open-company.org) 写好的公司。每家公司是一个目录，复制过去就可以用。第一批还在整理，所以本仓库目前只有占位页。

规范在 [open-company.org](https://open-company.org)。参考运行时 Munk AI 在 [munk.sh](https://munk.sh)。

页头和站点图标与规范站使用同一枚标志（`brand/logo.svg`）。

## 本地预览

在本目录起一个静态文件服务：

```bash
python3 -m http.server 4321
```

打开 <http://127.0.0.1:4321>。页头可切换中文 / English。
