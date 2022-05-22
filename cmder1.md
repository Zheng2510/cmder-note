### cmder
## 特点
* 一个还可以的控制台软件
* 内置gitbash，也支持cmd和powershell
* 不同时安装gitbash和cmder，重复了
* gitbash 不是git，是git公司出品的bash软件
* 支持一键呼出ctrl+`(esc下面）
* 支持分屏（自己设置一个快捷键）
* 可以换肤（推荐fira code或consoals 字体）
* 偶尔有bug 不要慌 杀死他（搜索）重开就好了

### 安装之后
### 自然就有了git命令
### 自然就有了一些linux上的命令


## 安装node.js
* 安装双数版 node8，10，12是稳定版
* 尽力选择官网安装

### 安装之后
### 自然就有了node命令（’因为path）
### path添加或者查看方法 右击此电脑--属性--高级系统设置--环境变量--双击path--新建
### 自然就有了npm命令
### 自然就有了npx命令

## 配置node.js
* 使用淘宝源(不要使用cnpm）
* 所有安装位置/c/users/admin/appdata/rouming/npm/http-sever
* cmder中输入
1. npm i -g nrm
2. nrm ls
3. nrm use taobao
4. npm i -g http-sever
5. http-sever --version
6. which http-sever

### 增删改查
* 程序员的宿命
* 学习文件的增删改查
* 学习ｄｏｍ的增删改查
* 学习http的增删改查

### 增:创建文件
* touch(创建文件) touch 1.txt
* echo(覆盖文件,展示最新)
* echo haha >>(追加) 2.txt
                   >(覆盖)
* echo -e(追加两行内容) "1\n" >> 4.txt (追加内容用"")

* mkdir(制作目录)
* mkdir a b 创建两个文件夹a,b
* 创建有层级的目录
* mkdir -p a/b/c/d/e 在a中创建b在b中创建c
* 同时创建多个文件
* touch 1.txt 2.txt
* 同时创建多个目录
* mkdir -p a/b/c a/e/u
* 复制文件 cp 1.txt(要复制的文件名) 2.txt(粘贴后的文件名)
* 复制目录 cp -r(重复) a b

* 删:删除文件
* rm(移动,删除) 1.txt
* rm -r a 删除目录(递归的删除)
* rm -rf a 直接删除(不管里面有没有内容)

### 系统文件决不能删

## 如何避免误删系统文件

* 给用户创建一个可以随便删的文件让他玩
* 这个目录就是用户目录
* 缩写为~(英文符号)

### 改:修改文件或者目录
* 修改内容(文件)
*  用code修改
    1. code 1.txt  打开code直接修改
   2. start 1.txt (将打开方式提前设置为用code打开)
   3. 用echo追加文件内容

### 清空文件
1. echo ''(两个单引号) >(覆盖) 1.txt (将空字符串追加到1.txt)
2. 打开文件,全部删除

### 移动文件或者目录

* mv 1.txt b(文件名)  把1.txt移动到文件夹里
* mv b/1.txt .(点)   把1.txt移动到当前目录

### 重命名文件/目录
* mv 1.txt 2.txt  将1.txt命名为2.txt

### 移动和重命名是同一操作

### 修改文件最后更新时间

* ls -l 查看编辑更新时间

* touch 文件名 修改文件更新时间

* ls --help l less(翻页查看)  查看帮助手册

* npm i -g tldr   解决帮助手册太长
或 yarn global add tldr
* tldr 一个命令的几种形式