#### 入口为index.html，随便一个静态服务器都可以，个人比较喜欢`browser-sync`, 即改即看效果，命令请参考：`browser-sync start --server --files '\''**/**.html,**/**.js'\''`

#### 运行
+ node端的代码在nodeServer下, 
+ cd nodeServer,
+ npm install, 安装所有的依赖,
+ node upload.js启动服务,
+ node环境就启动完成
#### *注意:node的版本必须>=7.6*, 因为里面使用了async和await语法, 属于ES7规范, 低版本Node不支持
#### 详细的原理和步骤，请参见文章：[Node+H5实现大文件分片上传](https://segmentfault.com/a/1190000008899001)
