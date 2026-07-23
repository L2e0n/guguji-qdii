# QDII 额度监控前端

静态页：`qdii.guguji.icu`（GitHub Pages，与 `ji.guguji.icu` 同模式）

- 本仓库只放前端静态资源，**不依赖本机开机**
- 数据 API：`https://ocr.guguji.icu/api/qdii/*`（阿里云 7x24 + Cloudflare Tunnel）
- 数据口径：东财申购状态 + 单日累计申购上限

## 本地预览

直接打开 `index.html`，或：

```bash
python -m http.server 5500
```

API 在 localhost 时会指向 `http://127.0.0.1:5000`，线上指向 `ocr.guguji.icu`。
