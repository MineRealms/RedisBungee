# RedisBungee | BC集群

This repo is MineRealms's fork of RedisBungee [RedisBungee](https://github.com/minecrafter/RedisBungee) 
[Redis](http://redis.io) and BungeeCord together. This is the solution deployed on [The Chunk](http://thechunk.net) to make sure our multi-Bungee setup flows smoothly together.

这是我的领域群组的RedisBungee分支，他可以通过Redis以BungeeCord来实现BC连接BC，轻而易举实现BC集群，或你所想的一切！

## Compiling | 编译

RedisBungee is distributed as a [maven](http://maven.apache.org) project. To compile it and install it in your local Maven repository:

RedisBungee是一个maven项目，想编译它你需要安装所需的Maven仓库

    git clone https://github.com/minecrafter/RedisBungee.git
    cd RedisBungee
    mvn clean install

## Configuration | 配置

**REDISBUNGEE REQUIRES A REDIS SERVER**, preferably with reasonably low latency. The default [config](https://github.com/minecrafter/RedisBungee/blob/master/src/main/resources/example_config.yml) is saved when the plugin first starts.

**REDISBUNGEE 需要一个REDIS服务器**以及最好在内网下搭建，延迟越小越好~
