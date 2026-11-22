# AGENTS.md

tech-posts-assets 的代理指示單一來源。Codex 與 Antigravity 直接讀這份，Claude Code 經 `CLAUDE.md` 的 `@AGENTS.md` 匯入。

## 這個 repo

這是公開 repo，放 tech-posts 文章用的圖片。文章原稿在私有 repo `tech-posts`，文章以公開網址引用這裡的圖。

## 規則

1. 只放已遮蔽、可公開的圖。原圖永遠不進這個 repo，也不要把未遮蔽的截圖當作暫存提交。
2. 路徑固定為 `<文章代號>/<序號>-<說明>.<副檔名>`，例如 `C4/03-argocd-sync.png`。代號是 A 到 H 加數字，或 M 加數字與可選的小寫尾碼（如 `M1a`），序號兩位數，說明只用小寫英數與連字號，副檔名限 png、svg、jpg、webp。
3. 除了 `README.md`、`.gitignore` 與 `.github/workflows/check-paths.yml`，不放其他檔案。CI 的 `check-paths` 會擋掉不符合路徑規則的檔案。
4. 遮蔽的方式與慣例寫在 `tech-posts` repo 的 `templates/README.md`，這裡不重複。
