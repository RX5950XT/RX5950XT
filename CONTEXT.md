# CONTEXT — RX5950XT GitHub Profile

個人首頁 repo：`RX5950XT/RX5950XT`（public）。

## README 結構

1. Hero：`claude-jump.gif` + tagline `build everything, break it, blame the agent`
2. **5×2 HTML `<table>`**（10 張情境 GIF + 標籤）
3. Contribution snake SVG

網格必須用 HTML table（2 tr × 5 td）。缺 separator 的 Markdown table 會直排並露出 `|`。

## assets/ 用途

| 檔案 | README 位置 | 標籤 | 用途 |
|------|-------------|------|------|
| `claude-jump.gif` | Hero | — | 登場／跳躍 |
| `claude-coding.gif` | 上 1 | tap tap | 寫 code |
| `claude-thinking.gif` | 上 2 | uhhh… | 卡住思考 |
| `claude-magnifier.gif` | 上 3 | where bug | 找 bug／debug |
| `claude-idea.gif` | 上 4 | wait. wait. | 靈感來了 |
| `claude-wand.gif` | 上 5 | ✨ yolo | AI 一鍵出貨 |
| `claude-welding.gif` | 下 1 | hot metal | 硬體／韌體焊接 |
| `claude-wrench.gif` | 下 2 | bonk fix | 硬修／重構 |
| `claude-error.gif` | 下 3 | oopsie | 炸掉／ERROR |
| `claude-bubbles.gif` | 下 4 | zen mode | 冷靜吹泡泡 |
| `claude-music.gif` | 下 5 | lofi.exe | 收尾聽音樂 |
| `github-contribution-snake.svg` | 底部 | — | snk 動態 contribution 蛇 |

## 規範

- 匿名：無學校／姓名／Email
- 檔名一律 ASCII
- Profile 不能 inline script／任意 CSS；動態靠 GIF／SVG／badge
- snk workflow 只更新 `github-contribution-snake.svg`，勿覆蓋其他素材

## 已知問題

Profile overview（`github.com/RX5950XT`）不掛 README，屬 special profile repo 綁定失敗。  
手動：網頁刪庫 → 新建同名並勾 Add a README → `git push -u origin main --force`。
