# module3_auto_build
自动化构建

### 使用说明
1. npm clone https://github.com/PeculiarCode/module3_auto_build.git
2. npm install 
3. npm link
4. ycli create module_name

**特别说明** 
如果出现Cannot find module或者File exists则将对应package.json目录的bin对象对应的key重命名为rename_cli执行npm link
最后执行rename_cli create module_name
### 构建说明
- 模拟vue-cli命令自定义ycli命令工具实现项目构建
- 通过在package.json加入ycli命令然后将该命令通过npm link映射到全局

### lib目录结构说明
- download用于执行克隆代码源文件
- exec用于执行命令
- install用于安装相应的依赖
- file用于更新package.json方法

### 本次作业分两个git上交地址分别为
- https://github.com/PeculiarCode/module3_auto_build
- https://github.com/PeculiarCode/module_3