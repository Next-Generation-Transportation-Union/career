# NGTU Careers Page

下一代人本交通促進會（NGTU）招募網站。

**Live**：[guanwei-cmd.github.io/carrer](https://guanwei-cmd.github.io/carrer)（啟用 GitHub Pages 後生效）
**主檔**：[`careers.html`](./careers.html)
**進入點**：[`index.html`](./index.html)（會自動跳轉到 `careers.html`）

---

## 內容

招募網站涵蓋：
- 2026 縣市首長候選人交通改善承諾白皮書行動介紹
- NGTU 三年里程（立法成果、遊行、政策諮詢）
- 工作文化與培力訓練說明
- 提供的數位工具（.org Email、Slack Pro、Claude Teams 規劃中）
- 5 個招募職位 + 自薦窗口
  - 議員資料研究員
  - 縣市聯絡夥伴
  - 拜訪排程與聯絡夥伴
  - 記者會與行政籌辦
  - 【Road for All】性別主流化專案研究夥伴
- FAQ

## 應徵流程

點擊任一職位的「投遞申請」按鈕會跳出彈窗，提示應徵者：

1. 將履歷寄送至 **`guanwei@ngtu.org`**
2. 信件主旨格式：**`【職位名稱】姓名`**

## 技術細節

- 純 HTML + CSS + JavaScript，無構建步驟、無依賴
- 響應式（含手機 hamburger menu）
- Google Fonts：Noto Sans TC + Inter
- 所有 SVG 圖示內嵌
- 視覺主色：NGTU 萊姆綠 `#c5ff40`

## 本地預覽

```bash
# 任何靜態伺服器都可以
python3 -m http.server 8000
# 開 http://localhost:8000/careers.html
```

或直接雙擊 `careers.html` 在瀏覽器打開。

## 部署選項

- **GitHub Pages**（推薦）：Repo Settings → Pages → Source = `main` branch / root
- **Cloudflare Pages**：Connect to GitHub → 自動部署
- **Surge**：`npx surge .` 一行搞定
- **Netlify Drop**：拖整個資料夾到 [app.netlify.com/drop](https://app.netlify.com/drop)
