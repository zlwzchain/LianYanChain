[![pipeline status](https://api.travis-ci.org/bityuan/bityuan.svg?branch=master)](https://travis-ci.org/bityuan/bityuan/)
[![Go Report Card](https://goreportcard.com/badge/github.com/bityuan/bityuan)](https://goreportcard.com/report/github.com/bityuan/bityuan)

# LianYanChain公有链系统

#### 编译

```
git clone https://github.com/zlwzchain/LianYanChain.git $GOPATH/src/github.com/zlwzchain/LianYanChain
cd $GOPATH/src/github.com/zlwzchain/LianYanChain
go build -i -o LianYanChain
go build -i -o LianYanChain-cli github.com/zlwzchain/LianYanChain/cli
```

#### 运行

拷贝编译好的LianYanChain, LianYanChain-cli, LianYanChain.toml这三个文件置于同一个文件夹下，执行：

```
./LianYanChain -f LianYanChain.toml
```
