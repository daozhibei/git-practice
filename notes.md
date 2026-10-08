# 学习笔记

## git 的三个区域

| 区域 | 说明 |
|---|---|
| 工作区 | 正在编辑的文件 |
| 暂存区 | git add 之后、commit 之前 |
| 仓库历史 | git commit 之后的永久版本 |

## 四步循环

改文件 -> git add -> git commit -m \"说明\" -> git push

## 状态符号（git status --short 的两个字符位）

- ?? 新文件，未被跟踪
-  M 已修改，未 add
- M  已修改，已 add
- A  新文件，已 add

## 分支的意义

main 是随时可用的主线；改动在分支上试错，试好了通过 Pull Request 合并回去。