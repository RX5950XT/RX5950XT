# CONTEXT — RX5950XT GitHub Profile

## 目的

GitHub 個人首頁 repo（username = repo name：`RX5950XT/RX5950XT`）。  
遠端：`https://github.com/RX5950XT/RX5950XT`（public，`main`）。

## 素材對照（`assets/`）

| 檔名 | 標籤 | 情境角色 |
|------|------|----------|
| `claude-jump.gif` | （hero） | 登場 |
| `claude-coding.gif` | tap tap | 寫 code |
| `claude-thinking.gif` | uhhh… | 卡需求 |
| `claude-magnifier.gif` | where bug | 調查 / debug |
| `claude-idea.gif` | wait. wait. | 靈感 |
| `claude-wand.gif` | ✨ yolo | AI 協作出貨 |
| `claude-welding.gif` | hot metal | 硬體 / 韌體 |
| `claude-wrench.gif` | bonk fix | 修 bug |
| `claude-error.gif` | oopsie | 炸掉 |
| `claude-bubbles.gif` | zen mode | 冷靜 |
| `claude-music.gif` | lofi.exe | 收尾 / 循環 |
| `github-contribution-snake.svg` | — | 動態 contribution |

## README 結構

1. Hero：`claude-jump.gif` + tagline `build everything, break it, blame the agent`
2. **5×2 HTML table**（10 張情境 GIF + 一字標籤）
3. Contribution snake SVG

### 網格注意

- 必須用 **HTML `<table>`**（2 `<tr>` × 5 `<td>`），勿用缺 separator 的 Markdown table（會被當成直列文字）。
- 每格 `width="20%"` + `align="center"`，無多餘行列。
- Profile README **不能** inline script / 任意 CSS；動態靠 SVG / badge / GIF。
- 貪吃蛇路徑：`assets/github-contribution-snake.svg`（snk workflow 勿覆蓋其他素材）。
- 檔名一律 ASCII。

## 規範

- Profile **維持匿名**：不放學校、系所、姓名、Email 等個資。
- 專案描述避免可識別身分的學校字樣。

## 已知問題（2026-07-15）

**Profile overview 不顯示 README**（`https://github.com/RX5950XT` 沒有 profile-readme）。  
repo 頁本身可正常渲染；屬 GitHub special profile repo 綁定失敗。

**手動修復（需登入網頁）：**
1. 刪除 `RX5950XT/RX5950XT`（Settings → Delete）
2. 一併刪多餘 tmp/backup repo
3. 網頁 **New repository** 名稱精準 `RX5950XT`，勾 **Add a README**
4. 本地 `git push -u origin main --force`

## 最近變更

- README 網格改 HTML table **5×2**，修掉 Markdown table 缺 separator 導致直排。
- 極簡：圖為主、每格短標籤；無 badge / CTA / 個資。
- assets ASCII 檔名。
