# ☁️ DevOps Engineer Roadmap 2026

從 Linux 到 production infrastructure 的 12 階段互動式學習路線圖。

**線上版本 → https://yu-0312.github.io/devops-roadmap/**

> Don't just deploy code. Build infrastructure that is automated, scalable, secure, and reliable.

---

## 這是什麼

一個單檔的靜態網站，把 DevOps 的學習路徑拆成 12 個可以依序推進的階段。每個階段包含：

- **為什麼重要** — 這階段解決的到底是什麼問題
- **學什麼** — 具體的主題清單，不是模糊的方向
- **關鍵指令** — 真的會天天打的那幾行，可一鍵複製
- **動手做** — 一個練習專案，做得出來才算過關
- **完成標準** — 可勾選的檢查清單，進度自動存在瀏覽器
- **推薦資源** — 免費且品質經得起考驗的學習來源

另外附一張跨階段的**指令速查表**，支援即時搜尋。

## 12 個階段

| # | 階段 | 建議時程 |
|---|------|---------|
| 1 | 🐧 Linux | 3–4 週 |
| 2 | 🌐 Networking | 2–3 週 |
| 3 | 🔧 Git + GitHub | 1–2 週 |
| 4 | 💻 Bash + Python | 3–4 週 |
| 5 | ☁️ Cloud（AWS / Azure / GCP） | 4–6 週 |
| 6 | 🐳 Docker | 2–3 週 |
| 7 | ⚙️ CI/CD（GitHub Actions / Jenkins） | 3–4 週 |
| 8 | 🏗️ Terraform / Infrastructure as Code | 3–4 週 |
| 9 | ☸️ Kubernetes | 6–8 週 |
| 10 | 📊 Monitoring + Observability | 3–4 週 |
| 11 | 🔐 Security + Secrets Management | 3–4 週 |
| 12 | 🚀 Deploy & Operate Production | 持續進行 |

全程約 9–12 個月，依每週投入時間而定。

## 本機執行

沒有建置步驟、沒有相依套件。

```bash
git clone https://github.com/Yu-0312/devops-roadmap.git
cd devops-roadmap
python3 -m http.server 8000   # 或直接用瀏覽器打開 index.html
```

然後開 http://localhost:8000

## 技術細節

- 單一 `index.html`，內嵌 CSS 與 JavaScript，零外部相依
- 進度存在 `localStorage`，**完全留在你自己的瀏覽器**，不會上傳到任何地方
- 支援深/淺色主題、鍵盤操作、行動裝置版面
- 透過 GitHub Actions 自動部署到 GitHub Pages

## 授權

MIT License — 自由使用、修改、分享。
