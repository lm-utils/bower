# bower
Bower —— 管理客户端软件包依赖关系

bower 的作用
   1. 可用于搜索、安装和卸载如JavaScript、HTML、CSS之类的网络资源
   2. 节省时间。一行代码搞定
   3. 可以展现客户端的依赖关系在bower.json文件
   4. 升级容易
bower 的使用
   1. 安装bower
    npm install -g bower
   2. 查看bower命令
    bower help
   3. 包的安装
    bower install jquery
bower.json文件的使用
   使用bower init 命令来创建bower.json文件：
    bower install bootstrap --save //--save参数是保存配置到你的bower.json
.bowerrc文件的作用
	自定义包的安装目录
	
	
参考文档：
	https://segmentfault.com/a/1190000000349555
   