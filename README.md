# 学习git
## 学习的网址
https://www.runoob.com/git/git-create-repository.html
## git创建仓库
1.凡是有$ 的都是在git bash上操作

2.在进行git操作的时候，注意要写全文件名称，加上后面的文件属性， 比如 Readme.md  
## git分支管理
1. git checkout -b <branchname> 中，-b 是一个选项，用于在切换分支的同时创建一个新的分支  
2. 两个分支间的更改互不影响，除非将分支融合，*例：* 当你从 feature/new-feature 分支切换回 testing 分支时，Git 会将工作目录中的文件状态还原到你在 testing 分支上的最后一次提交状态。换句话说，你在 feature/new-feature 分支上所做的更改不会反映在 testing 分支上，除非你将这些更改合并到 testing 分支。
3.  git rm 删除操作 git commit -am :a表示add, m表示message. **例子** :假设你有一个文件 example.txt，它已经被添加到版本库中。你对这个文件进行了修改，但还没有运行 git add。此时：1)如果你直接运行 git commit -m "提交信息"，Git 会报错，因为暂存区中没有任何内容。2)如果你运行 git commit -am "提交信息"，Git 会自动将 example.txt 的更改添加到暂存区，然后提交这些更改。
4.  当你在 Git 中从 master 分支（或任何其他分支）创建一个新的分支时，新分支会继承 master 分支在创建时的所有内容和提交历史。换句话说，新分支会从创建它的分支的当前状态开始，**复制所有文件和目录的内容**。  
5.  cat runoob.php 中 **cat**指显示文件的内容。**vim**:运行 vim 命令时，可以打开一个文本文件进行编辑，或者直接进入编辑模式创建新文件。然后进入vim的insert模式后，写东西，写完按Esc键退出，然后再打出 **:wq**， 就可以保存并退回到操作台界面。**:qa**：强制关闭并退出。:后单按一个q也是可以的
6.  遇到分支文件和主文件有冲突怎么办：手动修改，修改结束后用 add操作告诉git修改结束  
7.  恢复和回退：这个没太懂啊，遇到了再说吧
## git打标签  
1.  用于给仓库中的特定提交点加上标记，通常用于发布版本（如 v1.0, v2.0）。
2.  推荐使用git tag -a v1.0 这样的语法，-a表示有带注签的提交。
## 跳过了gitflow和git进阶用法
## github
1.  添加远程库：需要ssh key
