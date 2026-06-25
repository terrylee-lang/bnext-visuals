# bnext-visuals

《數位時代》互動視覺配件托管庫。所有 HTML 配件透過 GitHub Pages 部署，可在文章後台用 `<iframe>` 直接嵌入。

**入口**：[https://terrylee-lang.github.io/bnext-visuals/](https://terrylee-lang.github.io/bnext-visuals/)

---

## 配件清單

| 配件 | 對應文章 | 上線日 | 路徑 |
|------|----------|--------|------|
| bad 還是 sad？Claude Code 團隊的品質分級語言 | 深度分析「bad vs. sad：Anthropic Claude Code 團隊的品質分級框架」：把工程負責人 Fiona Fung 於 Lenny's Podcast 提出的兩級品質語言視覺化。bad（深 navy 強調卡）＝不可恢復的嚴重錯誤、sad（淺底輕卡）＝可恢復但讓人不舒服，中間橘色升級帶點出 sad 堆疊會滑向 bad、故 sad 也要追蹤趨勢；下接「各團隊自畫紅線」落地說明與 CLI／UI 範例。桌機兩級並列、手機單欄堆疊，純 CSS container query 雙軌 | 2026-06-25 | [`2026/06-claude-code-bad-vs-sad.html`](./2026/06-claude-code-bad-vs-sad.html) |
| 六天五人：Google AI 人才出走流向圖 | 即時新聞「六天五人：Google AI 人才出走流向圖」：一週內五名 Google／DeepMind 研究員傳出出走，桌機 SVG 流向圖把單一流出來源連到 Anthropic（4 人）與 OpenAI（1 人），三名 AlphaFold 核心成員（Jumper／Adler／Pritzel）傳於 Anthropic 重聚，用 BN Orange 高亮重聚集群；手機改依目的地分組人名清單。下接三數字看規模（Transformer 八作者七人離 Google、DeepMind 跳 Anthropic 約反向 11 倍、Anthropic 估值 9,650 億美元）。全程標明部分人事為彭博等媒體報導之傳出階段、尚未經官方證實 | 2026-06-25 | [`2026/06-google-ai-talent-exodus.html`](./2026/06-google-ai-talent-exodus.html) |
| 特斯拉 FSD（Supervised）全球開放進度 | 深度分析「特斯拉 FSD 送件台灣：排進一條跑了一年多的審查隊伍」：全球市場依開放階段分四級（已上路／道路測試／送審中／待核准），台灣標「送審中」並用 BN Orange 強調，凸顯後進者位置。中國標外電報導、比利時標業者口徑、家數採「逾十個市場」不咬死，頁首頁尾點明受駕駛監督的 L2、非無人駕駛 | 2026-06-16 | [`2026/06-tesla-fsd-global-rollout.html`](./2026/06-tesla-fsd-global-rollout.html) |
| 迴圈工程：五階段循環 × 六塊組件 | 教學文「Loop Engineering 是什麼」：五階段循環（探索→規劃→執行→驗證→迭代）與六塊組件（自動化／Worktree／技能／連接器／子代理／記憶）的互動對應圖，點組件亮對應階段。純 CSS 互動 | 2026-06-15 | [`2026/06-loop-engineering-cycle.html`](./2026/06-loop-engineering-cycle.html) |
| Claude Code Skill 的 9 種類型 | Anthropic「Lessons from building Claude Code」心法文：官方盤點內部數百個活躍 skill 歸納出的 9 種類型卡片地圖，幫讀者檢查還缺哪一種 | 2026-06-12 | [`2026/06-claude-skills-9types.html`](./2026/06-claude-skills-9types.html) |
| 一個 SKILL.md 長什麼樣？五個區塊拆給你看 | 同篇心法文：以「週報產生器」為例，拆解 SKILL.md 的 name／description／怎麼做／Gotchas／參考五區塊各自作用 | 2026-06-12 | [`2026/06-skillmd-anatomy.html`](./2026/06-skillmd-anatomy.html) |
| SpaceX 三大分部損益：誰在賺、誰在燒錢 | SpaceX 上市懶人包：2025 三大分部營收 vs 營業損益對照，星鏈賺的被 Space 與 AI 燒掉，整體營業虧損 25.89 億美元 | 2026-06-08 | [`2026/06-spacex-segment-pnl.html`](./2026/06-spacex-segment-pnl.html) |
| SpaceX 上市與解禁時間軸：賣壓何時來 | SpaceX 上市懶人包：上市流程（路演／定價／掛牌 SPCX）與三類股東鎖定期階梯式解禁節點，全依「預計／若如期」口徑 | 2026-06-08 | [`2026/06-spacex-ipo-lockup-timeline.html`](./2026/06-spacex-ipo-lockup-timeline.html) |
| 一顆矽光子晶片裡有什麼？跟著光走一遍 | 矽光子母題文「矽光子是什麼」段落內嵌平面示意圖（文章 77079）：同一顆封裝內發射鏈／接收鏈跟著光走 | 2026-06-03 | [`2026/06-silicon-photonics-explainer.html`](./2026/06-silicon-photonics-explainer.html) |
| 矽光子概念股供應鏈分層一覽 | 矽光子概念股一覽（文章 82171） | 2026-06-03 | [`2026/06-silicon-photonics-supply-chain.html`](./2026/06-silicon-photonics-supply-chain.html) |
| 2025 上市櫃員工平均年薪 TOP 25 | 上市櫃員工平均年薪出爐：半導體霸榜，日月光投控 628 萬居首 | 2026-06-02 | [`2026/06-listed-companies-avg-salary-top25.html`](./2026/06-listed-companies-avg-salary-top25.html) |
| 尹衍樑 1950–2026：潤泰總裁、唐獎創辦人 76 年大事記 | 潤泰集團總裁、唐獎創辦人尹衍樑辭世，享壽 76 歲 | 2026-05-26 | [`2026/05-yin-yenliang-memorial.html`](./2026/05-yin-yenliang-memorial.html) |
| 2027 請假攻略 8 種組合 CP 值一次看 | 2027 年行事曆出爐！9 大連假、春節放 7 天，補假日期一次看 | 2026-05-21 | [`2026/05-2027-leave-strategy.html`](./2026/05-2027-leave-strategy.html) |
| Anthropic Q2 規模化轉盈：營收倍增 × 單位成本下降 | Anthropic 可望首度單季轉盈：Q2 營收預估 109 億美元、季增 130% | 2026-05-21 | [`2026/05-anthropic-q2-profitability.html`](./2026/05-anthropic-q2-profitability.html) |
| SpaceX S-1 一頁讀懂：史上最大 IPO 的數字長什麼樣 | SpaceX 公開遞件赴納斯達克 IPO，擬募資最高 750 億美元 | 2026-05-21 | [`2026/05-spacex-ipo-s1.html`](./2026/05-spacex-ipo-s1.html) |
| 宜得利 vs 無印良品：兩條成長軌跡 | 日本兩大零售巨頭近 60 年營收對照 | 2026-05-20 | [`2026/05-nitori-vs-muji-growth.html`](./2026/05-nitori-vs-muji-growth.html) |
| Codex 長駐特助五招拆解 | 不是再多一個聊天機器人：Codex 如何變成你的「長駐 AI 特助」 | 2026-05-19 | [`2026/05-codex-long-running-assistant.html`](./2026/05-codex-long-running-assistant.html) |
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
