## 交作業流程

1. 新開一個 branch：`git branch hw1` (最重要)
2. 切換到 branch： `git checkout hw1`
3. 寫作業
4. 如果有新增的檔案，加入 git： `git add .`
5. 提交 commit：`git commit -am "hw1"`
6. 推到 GitHub：`git push origin master`
7. 到我的 repo 去，並且發起 PR（Pull Request）
8. 把 PR 的連結複製起來，並且在學習系統上繳交作業

等作業改完並且 merge 以後：

1. 切換到 master：`git checkout master`
2. 把最新的改動拉下來：`git pull origin master`
3. 刪除已經 merge 的 branch：`git branch -d hw1`
4. 大功告成
