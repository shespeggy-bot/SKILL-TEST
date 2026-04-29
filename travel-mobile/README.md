# 移动端旅游落地页

单文件 `index.html`（Tailwind CDN + Unsplash 配图）。外层深灰画布 + 内层奶油色圆角「手机画框」布局。

## 本地预览

```bash
cd travel-mobile
python3 -m http.server 8765 --bind 127.0.0.1
```

浏览器打开：<http://127.0.0.1:8765/>

**手机壳预览 + 二维码（750×1624 内屏）**：<http://127.0.0.1:8765/preview-frame.html>（须通过 HTTP 打开，扫码才指向可访问的 `index.html`）。

## 切图

设计导出的 PNG/SVG 可放在 `screenshots/` 便于版本管理；页面内大图目前为在线 Unsplash 地址。
