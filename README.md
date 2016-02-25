# bower
###Bower —— 管理客户端软件包依赖关系

	> Bower 是 twitter 推出的一款包管理工具，基于nodejs的模块化思想，把功能分散到各个模块中，让模块和模块之间存在联系，通过 Bower 来管理模块间的这种联系。  
###bower 的作用
   1. 可用于搜索、安装和卸载如JavaScript、HTML、CSS之类的网络资源
   2. 节省时间。一行代码搞定
   3. 可以展现客户端的依赖关系在bower.json文件
   4. 升级容易

###bower 的使用
   1. 安装bower  
    npm install -g bower  
   2. 查看bower命令  
    bower help  
   3. 包的安装  
    bower install jquery  

###bower.json文件的使用  
   > 使用bower init 命令来创建bower.json文件：  
   > bower install bootstrap --save //--save参数是保存配置到你的bower.json  
	
###.bowerrc文件的作用  
   > 自定义包的安装目录  
 
###用bower提交自己类库
	1. 打版本号  
	 git tag 0.1.0   
	 git push origin --tags   
	2. 在bower中注册一下你的项目,输入以下命令执行后，选择y  
     bower register <my-package-name> <git-endpoint>
	3. 安装自己的包  
		bower install --save-dev package 
	4. 删除bower平台上的插件  
	  > bower login      
		# enter username and password    
		? Username:      
		? Password:    
		# unregister packages after successful login      
		bower unregister <package>  

	
参考文档：  
	https://segmentfault.com/a/1190000000349555  
	http://blog.fens.me/nodejs-bower-intro/  
	http://blog.csdn.net/itpinpai/article/details/49932151
   