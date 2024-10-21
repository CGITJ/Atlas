- I am TJ
- CREATED BY [CGITJ](https://github.com/CGITJ)
- 请遵守GPL开源协议，切勿滥用盈利！
- For：
- Notion，Obsidian，Flomo，Craft，石墨，幕布，飞书，语雀

# 贡献导引
请严格按照以下步骤操作，如有任何问题，请提出 issue
- 在 GitHub 上点击 fork 将本仓库 fork 到自己的仓库，如 yourname/Atlas，然后 clone 到本地
```Linux
$ git clone git@github.com:yourname/Atlas.git
$ cd Atlas
# 将项目与上游关联
$ git remote add source git@github.com:DocsHome/Atlas.git
```
- 增加内容或者修复错误后提交，并推送到自己的仓库
```Linux
$ git add .
$ git commit -am "Fix issue #1: change helo to hello"
$ git push origin master
```
- 在 GitHub 上提交 pull request
- 请定期更新自己仓库内容
```Linux
$ git fetch source
$ git rebase source/master
$ git push -f origin master
```