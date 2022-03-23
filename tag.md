标签管理
  查看所有标签 git tag
  打标签 git tag <tag_name>//一般合并到主分支再打标签，git tag v2.7.0.0
  查看commit历史及commit id git log - -pretty=oneline - -abbrev-commit
  给特定的commit id打tag git tag <tag_name>
  打tag,并且简要说明tag内容，类似于注释 git tag -a <tag_name> -m"内容"
  推送特定tag git push origin <tag_name>
  一次推送全部tag git push origin --tags
  删除标签 git tag -d <tag_name>//删除本地标签，git tag -d v2.7.0.0
  删除已推送到远程的标签 git push origin ：refs/tags/<tag_name>”//先删除本地的
  
  -------------------------------------------------------------
