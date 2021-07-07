# go-lab
go练习

## 开发环境搭建
### 环境变量
GOROOT  go的目录
PATH    把bin目录添加到系统path
GOPATH  工作目录

### vscode tool被墙 更改代理
$ go env -w GO111MODULE=on
$ go env -w GOPROXY=https://goproxy.io,direct

### 安装以下14个插件
Installing 14 tools at GOPATH
  gocode
  gopkgs
  go-outline
  go-symbols
  guru
  gorename
  gomodifytags
  goplay
  impl
  godef
  goreturns
  golint
  gotests
  dlv

Installing github.com/nsf/gocode SUCCEEDED
Installing github.com/uudashr/gopkgs/cmd/gopkgs SUCCEEDED
Installing github.com/ramya-rao-a/go-outline FAILED
Installing github.com/acroca/go-symbols FAILED
Installing golang.org/x/tools/cmd/guru FAILED
Installing golang.org/x/tools/cmd/gorename FAILED
Installing github.com/fatih/gomodifytags SUCCEEDED
Installing github.com/haya14busa/goplay/cmd/goplay SUCCEEDED
Installing github.com/josharian/impl FAILED
Installing github.com/rogpeppe/godef SUCCEEDED
Installing sourcegraph.com/sqs/goreturns FAILED
Installing github.com/golang/lint/golint FAILED
Installing github.com/cweill/gotests FAILED
Installing github.com/derekparker/delve/cmd/dlv SUCCEEDED

注意：安装这些插件之前需要去github官网中下载对应的库，然后根据错误提示去GOPATH中的src目录中创建对应的目录（文件夹）即可。然后再次安装就会成功
