# TrendLife Projects

TrendLife 品牌傘下的 prototypes / mockups repo。

## 基本資訊

- **GitHub**: https://github.com/amigacyc/TrendLife
- **Pages**: https://amigacyc.github.io/TrendLife/
- **Repo 根目錄（本機）**: `/Users/amiga_chin/Claude/Projects/TrendLife/`

## 專案清單

| 專案 | 主檔 | Pages URL |
|---|---|---|
| SocioFuture | `SocioFuture/prototype.html` | https://amigacyc.github.io/TrendLife/SocioFuture/prototype.html |

## 結構規則

- 每個專案一個資料夾（例如 `SocioFuture/`）
- 專案主檔命名 `prototype.html`
- 每個專案資料夾內放一個 `index.html`，redirect 到該專案的 prototype
- 根目錄 `index.html` redirect 到當前主推專案的 prototype

## 本機專屬檔案（不上 GitHub）

- `*/TMSC/` — mockup 素材、backup、design tokens 等本機工作檔（已 gitignored）
- `.DS_Store` — macOS 系統檔（已 gitignored）

## Pages 設定

- `.nojekyll` 存在，跳過 Jekyll 處理，直接 serve 靜態檔
- 推到 `main` 分支就會自動 rebuild（約 30–60 秒）

## 更新流程

1. 編輯對應專案的 `prototype.html`
2. `git add . && git commit -m "..." && git push`
3. 等 Pages rebuild → 開 URL 驗證

## 新增專案

1. 在 repo 根建新資料夾 `<ProjectName>/`
2. 放 `prototype.html` 和 `index.html`（redirect 到 prototype）
3. 更新本檔案的專案清單
4. commit + push
