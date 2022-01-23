# lidaxin11
git 操作
如何使用git将分支branch合并到主干master上
1 新建分支并切换
  git chechout -b <branchName>
  git add README.MD
  git commit -m "增加系统维护模块"
  git branch
2 切换到主干master
  git checkout master
  git merge <branchName>
  git push origin
3 合并后删除分支信息
git branch -d <branchName>