# bnext-visuals

《數位時代》互動視覺配件托管庫。所有 HTML 配件透過 GitHub Pages 部署，可在文章後台用 `<iframe>` 直接嵌入。

**入口**：[https://terrylee-lang.github.io/bnext-visuals/](https://terrylee-lang.github.io/bnext-visuals/)

---

## 配件清單

| 配件 | 對應文章 | 上線日 | 路徑 |
|------|----------|--------|------|
| Anthropic 創辦人劇本 4 階段地圖 | Anthropic 官方發布新創 AI 使用指南 | 2026-05-18 | [`2026/05-anthropic-founders-playbook.html`](./2026/05-anthropic-founders-playbook.html) |
| 2026 全球企業裁員追蹤 | 2026 裁員潮全解析 | 2026-05-18 | [`2026/05-layoffs-tracker.html`](./2026/05-layoffs-tracker.html) |

---

## 嵌入方式（後台 iframe 模板）

複製以下程式碼到文章編輯器的 HTML 模式，替換 `src` 與 `title`：

```html
<iframe src="https://terrylee-lang.github.io/bnext-visuals/2026/05-layoffs-tracker.html"
        width="100%" height="2800"
        style="border:0; max-width:880px; display:block; margin:24px auto;"
        loading="lazy"
        title="2026 全球企業裁員追蹤">
</iframe>
```

**高度建議**：

| 配件類型 | 建議 height |
|---|---|
| 短型統計卡（單一圖表） | 600–800 |
| 中型（圖 + 重點清單） | 1200–1800 |
| 長型 tracker（圖 + 完整清單） | 2600–3200 |

手機版內容若比桌機高（例如本案例的編年清單），取較大值為佳，桌機底部最多留一點空白不會難看。

---

## 檔案命名規範

`年份/MM-主題-kebab-case.html`

範例：
- `2026/05-layoffs-tracker.html`
- `2026/06-openai-revenue-breakdown.html`
- `2026/07-tsmc-fab-map.html`

英文 kebab-case，避免中文檔名造成 URL 編碼問題。

---

## 注意事項

- **Repo 為 public**：HTML 配件公開可見（本來就要嵌進公開文章），但**禁止放未發布稿件、API key、客戶名單、財報內部數據**
- **CDN 快取**：改完 HTML 後 1–5 分鐘 GitHub Pages 才更新，前台讀者可能看到舊版。要強制刷新可在 iframe URL 後加 `?v=20260518` 等版本參數
- **手機測試**：每次新配件 push 後，用 Chrome DevTools `Cmd+Opt+I` → 切手機尺寸（建議測 iPhone 14 Pro / Pixel 7）驗一輪
- **iframe 高度**：寫死高度，桌機與手機取較大者；未來如需動態調整可加入 `postMessage` 機制

---

## 啟用 GitHub Pages

1. Repo 上方 **Settings** → 左側 **Pages**
2. **Source** 設 `Deploy from a branch`
3. **Branch** 選 `main`、目錄選 `/ (root)`
4. **Save**
5. 2–5 分鐘後上方會出現 `Your site is live at https://terrylee-lang.github.io/bnext-visuals/`

⚠️ **必要前置**：repo root 必須有 `.nojekyll` 空檔，否則 GitHub Pages 預設用 Jekyll 處理，會自動忽略 `_assets/` 等 underscore 開頭的目錄，導致自托管 logo / CSS 全部 404。本 repo 已備有 `.nojekyll`。

---

## 結構

```
bnext-visuals/
├── README.md              # 本檔
├── index.html             # 配件總覽入口頁
├── _assets/               # 共用資源（字體、CSS）
│   └── .gitkeep
├── 2026/
│   └── 05-layoffs-tracker.html
└── 2025/                  # 之後依年份遞增
```

---

## 新配件工作流

1. Claude 在 vault `draft/` 產出 HTML 配件
2. 複製到 `bnext-visuals/<年份>/<MM-主題>.html`
3. `git add . && git commit -m "add: 配件描述" && git push`
4. 等 1–5 分鐘，GitHub Pages 更新完
5. 在 [`index.html`](./index.html) 與本檔配件清單表格加入新條目
6. 用 iframe 嵌入文章後台

---

維護：李先泰 ([edit@bnext.com.tw](mailto:edit@bnext.com.tw))
