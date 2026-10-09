# my-first-pr

這是我用來練習 GitHub Pull Request 的儲存庫。

## 開 PR 的基本流程

1. 從 `main` 開一個新分支：`git switch -c 分支名稱`
2. 修改檔案，然後 commit：`git add .`、`git commit -m "說明"`
3. 推送分支到 GitHub：`git push -u origin 分支名稱`
4. 開 Pull Request：`gh pr create`
5. 檢查改動沒問題後，在 GitHub 上按 **Merge** 合併

## 環境設定備忘

- 安裝 GitHub CLI：`winget install --id GitHub.cli --source winget`
- 登入 GitHub：`gh auth login`
- 確認登入狀態：`gh auth status`
