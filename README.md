## Forum App by Go

## Requirements

- Go 1.3+
- MySQL
- Memcached
- Node.js && node-sass, coffee-script

## Install

### For Assets Pipeline

```bash
$ npm install -g node-sass@2.0.1
$ npm install -g coffee-script@1.6.2
```

### Download & Install Go:

https://golang.org/dl/

## Clone source code, and run:

```
cd $GOPATH/src
git clone https://github.com/huacnlee/mediom.git
cd github.com/huacnlee/mediom
go get
go get github.com/revel/cmd/revel
revel run github.com/huacnlee/mediom
```

## Release for production

```bash
GOOS=linux GOARCH=amd64 revel package github.com/huacnlee/mediom
```

## Example

![](https://ruby-china-files.b0.upaiyun.com/photo/2015/54b8a61176321df2ae0c8d170115ae3b.png)

![](https://ruby-china-files.b0.upaiyun.com/photo/2015/cdd04fae02d0b78a3cf523e6abf5b198.png)

## Try it online:

http://115.29.238.54