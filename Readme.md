# 项目介绍

商城的 proto 目录文件

## 快速开始

使用 `protoc` 命令生成对应的文件，您可以选择任意的适配语言，生成对应的 protobuf 类

实例：Golang

```
protoc user.proto --go_out=plugins=grpc:.
```