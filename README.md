# mp-fonts

Web-optimized, single-file WOFF2 Chinese fonts with global jsDelivr CDN acceleration and CORS support, tailored for the `mp-look` miniprogram and modern web readers.

## 字体清单与 CDN 直链

| 字体名称 | 格式 | 体积 | 开源协议 | jsDelivr CDN 直链 |
| :--- | :--- | :--- | :--- | :--- |
| **传统宋体** (FandolSong-Regular) | WOFF2 | ~3.2 MB | GPL with Font Exception (免费商用) | `https://cdn.jsdelivr.net/gh/wangx7/mp-fonts@main/FandolSong-Regular.woff2` |
| **传统楷体** (FandolKai-Regular) | WOFF2 | ~4.3 MB | GPL with Font Exception (免费商用) | `https://cdn.jsdelivr.net/gh/wangx7/mp-fonts@main/FandolKai-Regular.woff2` |
| **汇文明体** (Huiwenmincho-improved) | WOFF2 | ~7.9 MB | 免费商用 (特里王 / 社区修正) | `https://cdn.jsdelivr.net/gh/wangx7/mp-fonts@main/Huiwenmincho-improved.woff2` |

## 特性
- **全网 CORS 支持**：jsDelivr 原生支持 `Access-Control-Allow-Origin: *`，适配微信小程序 `wx.loadFontFace` 与 Web 端。
- **高压缩率**：采用 Google Brotli 算法压缩为单文件 WOFF2，相较原版 OTF/TTF 减少 35%~68% 体积。
- **高可用全球加速**：基于 jsDelivr 多云 CDN（Cloudflare + Fastly + Gcore）全球分发。
