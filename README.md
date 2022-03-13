# 一键vps系列管理脚本

```shell
wget -N https://cdn.jsdelivr.net/gh/Misaka-blog/MisakaLinuxToolbox@master/MisakaToolbox.sh && chmod -R 777 MisakaToolbox.sh && bash MisakaToolbox.sh
```
快捷方式 `bash MisakaToolbox.sh`

# Acme.sh 域名证书一键申请脚本

此脚本可以帮助你使用acme.sh脚本申请域名的ssl证书，并且可以保存到你想要的位置

```shell
wget -N https://raw.githubusercontent.com/Misaka-blog/acme-1key/master/acme1key.sh && chmod -R 777 acme1key.sh && bash acme1key.sh
```

快捷方式 `bash acme1key.sh`

# 一键安装status监控

```shell
wget -N --no-check-certificate https://raw.githubusercontent.com/stilleshan/ServerStatus/master/status.sh && chmod +x status.sh && bash status.sh c
```
# 一键sillyGirl
```shell
s=sillyGirl;a=arm64;if [[ $(uname -a | grep "x86_64") != "" ]];then a=amd64;fi ;if [ ! -d $s ];then mkdir $s;fi ;cd $s;wget http://github.yanyuge.workers.dev/https://github.com/cdle/${s}/releases/download/main/${s}_linux_$a -O $s && chmod 777 $s;pkill -9 $s;$(pwd)/$s
```
# 一键安装docker-compose
```shell
curl -L "https://github.com/docker/compose/releases/download/1.29.2/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose && chmod +x /usr/local/bin/docker-compose
```
##查看docker-compose版本
```shell
docker-compose --version
```
