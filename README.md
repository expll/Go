
# go centos环境搭建
```
下载：https://go.dev/dl/
go1.20.5.linux-amd64.tar.gz
解压
tar -zxvf go1.20.5.linux-amd64.tar.gz
解压后go目录放置在
/usr/local/go
配置环境变量：~/.bashrc
# GO语言的环境变量设置：
GOROOT=/usr/local/go
GOPATH=/root/work/go
PATH=$PATH:$GOROOT/bin:$GOPATH/bin
source ~/.bashrc # 当前环境，即使重启机器也会生效
```

