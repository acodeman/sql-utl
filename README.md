# MongoDB
## windwos下安装mongodb
### 配置环境变量
```bash
D:\workprogram\MongoDB\Server\3.6\bin
```

### 创建配置文件**mongod.config**
```bash
##database directory
dbpath=d:\workprogram\MongoDB\data  
##log file  
logpath=d:\workprogram\MongoDB\log  
logappend=true  
```
文件位置在bin目录

### 在window中创建MongoDB服务
使用管理员身份运行cmd,并输入命令：
```bash
mongod --config D:\workprogram\MongoDB\Server\3.6\bin\mongod.config --serviceName MongoDB
```

### 删除MongoDB服务
```shell
SC DELETE MongoDB
```
