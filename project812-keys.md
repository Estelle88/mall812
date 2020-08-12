####2.自定义指令-lintfix

1.结尾没有;
2.必须用全等
3.不允许出现未使用得变量
4.不允许出现一个以上空行

> 在package.json中script自定义指令：指令很长
> npm run 自定义指令名(dev)
> npm run lintfix(自动按照规范修正全部的js代码)
> 自动打开浏览器 dev:'xxxxx --open'

>关闭eslint build/webpack.base.conf.js 注释掉42行,去掉规则(//...(config.dev.useEslint ? [createLintingRule()] : []),)


####3.elementUI安装-引入
> npm i element-ui -S
> 在main.js import
> Vue.use(ElementUI)

####5.项目准备-项目模板简化
> 删除模板中我们用不到的文件/代码

####6.项目-准备-git版本控制
> git/svn
1. git init --> .git
2. git status
3. git add .
4. git commit -m 'zhushi'
5. 在代码托管平台(github)新建远程仓库
6. git push