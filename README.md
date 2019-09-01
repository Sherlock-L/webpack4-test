## 入门教程
https://segmentfault.com/a/1190000006178770?utm_medium=referral&utm_source=tuicool&from=singlemessage#articleHeader5

## 可能的问题：
- 1.在npm install 时 注意对应的webpack版本 和webpack-cli的安装
- 2.配置css-loader 的 localIdentName ，可能会报错 报未定义这个属性
- 3.babel-loader和babel-core版本不对应产生问题 https://segmentfault.com/a/1190000016892088?utm_source=tag-newest
https://blog.csdn.net/zr15829039341/article/details/86553652 
- 4.注意npm install 时要根据情况选择全局或者当前目录安装。要保持一致

## 命令
下面都是自定义的命令 在package 里配置。执行webpack命令默认会读取当前目录下的webpack.config.js 的配置打包。
- npm run start 打包
- npm run server 使用webpack构建本地服务器