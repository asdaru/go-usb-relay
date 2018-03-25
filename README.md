# go-usb-relay-driver
[![godoc reference](https://godoc.org/github.com/mengzhuo/go-usb-relay?status.png)](https://godoc.org/github.com/mengzhuo/go-usb-relay)

Pure Go USB relay driver for cheap usb hid interface relay

Linux x86/amd64/armv5 is supported for now.

![](https://github.com/mengzhuo/go-usb-relay/raw/master/use-relay-slots1.jpg)


### Install
```
go get -v -u github.com/mengzhuo/go-usb-relay/g-relay
g-relay -h
# turn on num 1
g-relay -n 1 -o
```
