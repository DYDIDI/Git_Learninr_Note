# 学习git
## 学习的网址
https://www.runoob.com/git/git-create-repository.html
## git创建仓库
1.凡是有$ 的都是在git bash上操作

2.在进行git操作的时候，注意要写全文件名称，加上后面的文件属性， 比如 Readme.md  
## git分支管理
1. git checkout -b <branchname> 中，-b 是一个选项，用于在切换分支的同时创建一个新的分支  
2. 两个分支间的更改互不影响，除非将分支融合，*例：* 当你从 feature/new-feature 分支切换回 testing 分支时，Git 会将工作目录中的文件状态还原到你在 testing 分支上的最后一次提交状态。换句话说，你在 feature/new-feature 分支上所做的更改不会反映在 testing 分支上，除非你将这些更改合并到 testing 分支。
3.  git rm 删除操作
4.  当你在 Git 中从 master 分支（或任何其他分支）创建一个新的分支时，新分支会继承 master 分支在创建时的所有内容和提交历史。换句话说，新分支会从创建它的分支的当前状态开始，**复制所有文件和目录的内容**。
