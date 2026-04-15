将当前项目的所有代码变更同步到 GitHub 仓库：

1. 运行 `git status` 查看当前变更
2. 用 `git add` 添加所有有意义的变更文件（排除 .env 等敏感文件）
3. 根据变更内容生成一个简洁准确的 commit message
4. 运行 `git commit` 提交
5. 运行 `git push origin main` 推送到远程仓库
6. 如果远程有内容而本地没有，先 `git pull --rebase` 再 push
7. 完成后告诉我推送结果

注意：commit message 用英文，简洁描述变更内容。
