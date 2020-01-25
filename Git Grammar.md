## 上

+ git --version  //查看当前git版本号
+ git init  //初始化本地仓库
+ touch <文件名>  //创建文件
+ git config --global user.name 'Davis-Samuel'  //
+ git config --global user.email '915660715@qq.com'  //
+ git add <file> //添加文件
+ git status  //查看仓状态
+ git commit -m  //将文件提交到提交区，并添加备注
+ git push  //推送至远程仓库
+ git pull  //从远程仓库拉取数据
+ git clone  //从远程仓库拷贝数据
+ git add <指定文件名>  //将文件添加进缓存区
+ git add .  //将全部文件添加进缓存区
+ git rm --catch <文件名>  //删除当前文件
+ git add *.html  //添加某一类文件，如其后缀名为 .html 的文件
+

## 中

+ git touch .gitignore //创建一个忽略文件，将想忽略的文件的名字及其扩展名，写入.gitignore文件中并保存。
+ git branch <分支名称>  //创建一个分支
+ git checkout <分支名称>  //从master切换到分支中去。
+ '当在分支路径上时，文档中会显示master的文档内容和分支的文档内容，如果checkout回master时，那么分支中文档内容就不见了。那么此时就需要合并分支，将master和分支合并就可以看到双方共同的文档及内容了。当在分支路径时，对master中的文件进行修改，如果checkout切换回master，则修改不起作用。所以在分支中的修改对master中文档内容是不影响的。'
+ git checkout -b <分支名称>  //创建d分支并直接切换到d分支，等同于以上2个步骤
+ git checkout master  //从分支切换回master中去。
+ git merge <分支名称>  //在master路径的前提下，合并分支

## 下

+ 将本地仓库存到远程仓库GitHub中需要
例子：git remote add origin https://github.com/Davis-Samuel/Git-Grammar.git
git push -u origin master
如果已经建立了连接，则直接git push -u origin master
(注意要是用HTTPS)
+ 如果仓库名字与你的名字相同，则仓库名字可以直接作为一个服务器去进行浏览器访问
+ [fork别人的仓库放到自己新建的仓库，修改提交，并pull变为原来的仓库](https://blog.csdn.net/xc_zhou/article/details/87984242)

