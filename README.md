# git-skills

Git 提交与 pre-commit 工作流技能。技能目录直接位于仓库根目录，供其他技能仓通过 Git subtree 纳入自己的 `skills/git/` 目录。

| 技能 | 用途 |
| --- | --- |
| [git-commit-push/](git-commit-push/) | 提交、rebase 并推送当前分支 |
| [fix-with-pre-commit/](fix-with-pre-commit/) | 在明确的文件范围内修复并复验 pre-commit 错误 |

`git-commit-push` 依赖 `fix-with-pre-commit`。两个技能从 [backend-skills](https://github.com/lihuanshuai/backend-skills) 的 `5870a199cfdf9007e90233fdcad93c8d0dc1a33f` 迁入。
