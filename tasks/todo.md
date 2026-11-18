# RX5950XT todo
最後更新：2026-11-19

## 現況（交接）
- 個人 GitHub Profile repo（public）。README 由上而下：Hero（`claude-jump.gif` + tagline）→ 5×2 情境 GIF 網格 → contribution snake SVG → Rick roll GIF（滿寬、無字幕）。
- 網格必須用 HTML `<table>`（2 tr × 5 td）；缺 separator 的 Markdown table 會直排並露出 `|`。
- 素材都在 `assets/`，檔名一律 ASCII；GIF 位置與標籤以 README 為準。
- snake workflow（`.github/workflows/snake.yml`，每天 UTC 00:00 + 手動）只更新兩張 `github-contribution-snake*.svg`（淺色／深色用 `<picture>` 切換），勿覆蓋其他素材。

## 規範
- 匿名：不放學校、姓名、Email。
- Profile 不能用 inline script 或任意 CSS；動態效果只靠 GIF／SVG／badge。

## 已知問題
- Profile overview（`github.com/RX5950XT`）沒有掛上 README，屬 special profile repo 綁定失敗。
  修法（需使用者在網頁操作）：刪庫 → 新建同名並勾 Add a README → `git push -u origin main --force`。
