#  README.md

- 此项目为对redis源码进行修改学习

### 添加获取redis二进制路径

- getPathCommand
  
#### Usage

- getpath name
```sh
127.0.0.1:6379> getpath redis-cli
127.0.0.1:6379> /usr/bin/redis-cli

127.0.0.1:6379> getpath redis-server
127.0.0.1:6379> /usr/bin/redis-server
```