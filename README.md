self-shell-funcs for linux Ubuntu
================



### 在.bashrc文件中通过调用自己创建的Shell命令来简化Terminal中的命令.
在.bashrc 中加入 `source ~/ShellFuncs/.myFunc`即可
.myFunc 文件用来汇总所有类型Function
各个类型的Function可以自行在对应的 **.XXXFuncs** 文件里面修改.

---
# 目前添加的通用简化命令

#### (由于有部分命令是个人使用,在此就不做介绍了)

## cdfuncs
* **..**  返回上一级目录,并打印出该路径中所有文件及目录.
* **2..** 返回上两级目录,并打印出该路径中所有文件及目录.
* **3..** 返回上三级目录,并打印出该路径中所有文件及目录.
* **ro** 返回到根目录,并打印出该路径中所有文件及目录.
* **c** `cd`到对应路径,并打印出该路径中所有的文件及目录.

## launchfuncs
* **xmind** 开启xmind.
* **chrome** 后面跟一个参数,用chrome开启输入的网页.
* **lava** 用chrome开启lavaradio.com **(baidu,github,taobao等同理)**
* **ast** 开启Android-studio,得自己设置studio.sh路径.
* **tb** 开启thunderbird.
* **wz** 开启为知笔记.
* **genym** 开启Genymotion,Android模拟器.

## gitfuncs
* **st** 代替`git status -sb`.
* **adda** 代替`git add .`.
* **commit** 代替`git commit -m`,后面跟不加空行和&的commit信息.
* **commita** 代替`git commit -a -m`,同上.
* **amend** 代替`git commit --amend`.
* **pull** 代替`git pull origin master`,从master分支上pull.
* **pullr** 代替`git pull --rebase origin master`,pull的同时rebase.
* **push** 代替`git push origin master`,push到master分支上.
* **gl** 代替 `git log --all --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative;`,查看git commit日志.

## otherfuncs
* **cr** 代替`clear`.
* **mk** 代替`mkdir`,同时`cd`到创建的目录下.
* **rf** 代替`rm -rf`.
