
##使用说明-windows
在根目录放置"node.exe"以及"node.lib"文件
//安装
npm i
//运行
npm start
//打包
npm run-script packager-windows


##使用说明-mac
修改如下代码：
1、index.html: 
	"node = spawn(".\\node", ["./express-app/bin/www"], {"==>"node = spawn("./node", ["./express-app/bin/www"], {"
2、运行
	npm run-script start-mac
3、打包命令
	npm run-script packager-mac