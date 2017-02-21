# npm-test
npm包发布练习

参考：http://www.tuicool.com/articles/I3yMB37

##使用说明
1、注册npm账号。

2、将项目下载到本地，安装node环境，在项目目录下执行npm publish（需要修改package.json文件中的name属性，保证npm中没有对应的名称）。

3、npm 安装自己的包。本地执行命令即可看到效果。
以本项目为例：
```
npm install lifei-npm-test -g //安装自己的上传的npm包用于测试
npmtest -V //输出版本号信息
npmtest -h //查看帮助信息
npmtest //在当前目录下生成.npmrc文件
```
