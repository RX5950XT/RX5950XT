# CONTEXT — RX5950XT GitHub Profile

## 目的

GitHub 個人首頁 repo（username = repo name：`RX5950XT/RX5950XT`）。  
遠端 profile repo 尚未建立（`gh repo view` 404）。

## 素材對照（`assets/`）

| 檔名 | 原名 | 情境角色 |
|------|------|----------|
| `claude-jump.gif` | 跳躍 | Hero 登場 |
| `claude-coding.gif` | 電腦 | Boot / 寫 code |
| `claude-thinking.gif` | 思考 | 卡需求 |
| `claude-magnifier.gif` | 放大鏡 | 調查 / debug |
| `claude-idea.gif` | 燈泡 | 靈感 |
| `claude-wand.gif` | 魔法棒 | AI 協作出貨 |
| `claude-welding.gif` | 焊接 | 硬體 / 韌體 |
| `claude-wrench.gif` | 板手 | 修 bug / 重構 |
| `claude-error.gif` | error | 炸掉 |
| `claude-bubbles.gif` | 吹泡泡 | 冷靜 |
| `claude-music.gif` | 聽音樂 | 收尾 / 循環 |
| `github-contribution-snake.svg` | snk 產物 | 動態 contribution |

## 注意

- Profile README **不能** inline script / 任意 CSS；動態靠外部 SVG / badge / GIF。
- GitHub 對 **img 內嵌 SVG** 通常可播 CSS 動畫（snake）。
- 貪吃蛇由 snk workflow 產生時，勿覆蓋其他素材；路徑請對準 `assets/github-contribution-snake.svg`。
- 中文檔名已改為 ASCII，避免 CDN / raw 路徑編碼問題。

## 規範

- Profile **維持匿名**：不放學校、系所、姓名、Email 等個資。
- 專案描述避免可識別身分的學校字樣（repo 名若已公開另當別論）。

## 已知問題（2026-07-15）

**Profile overview 不顯示 README**（`https://github.com/RX5950XT` 沒有 markdown-body / profile-readme）。  
已驗證：
- repo 公開、名稱 = username、root 有 `README.md`、內容非空
- repo 頁 `https://github.com/RX5950XT/RX5950XT` 正常渲染全部 GIF + snake
- 極簡 README / auto_init 預設模板也無法掛到 overview
- 多次 rename 重建、切 private/public 無效

屬 GitHub 端「special profile repo」綁定失敗（類似 community #193747）。  
API token 無 `delete_repo` scope，無法從 CLI 完整刪庫重做。

**手動修復（需登入網頁）：**
1. 刪除 `RX5950XT/RX5950XT`（Settings → Delete）
2. 一併刪多餘：`RX5950XT-tmp-profile`、`RX5950XT-content-backup`
3. 用網頁 **New repository**，名稱精準 `RX5950XT`，勾 **Add a README**（應出現 special repository 提示）
4. 本地再 `git push -u origin main --force`

## 最近變更

- 重做 profile README：11 張 Claude GIF 劇情 + snake + 專案 + stats。
- assets 改 ASCII 檔名；移除個資；history rewrite 無學校字樣。


