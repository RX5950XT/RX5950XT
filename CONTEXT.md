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

## 最近變更

- 重做 profile README：用 11 張 Claude GIF 串成「一天日常」敘事 + snake + 精選專案 + stats。
- assets 全數 rename 為 kebab-case 英文檔名。
- 移除個資文案；rewrite commit 清除歷史中的個資。

