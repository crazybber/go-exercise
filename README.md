# 说明 instruction

if you want to find ***go-awesome-patterns** you can check : [Go Patterns(go-awesome-patterns)](https://github.com/crazybber/go-awesome-patterns)

如果你是冲着 **go的各种实践模式(包含常用设计模式)**,看这里：[Go模式(go-awesome-patterns)](https://github.com/crazybber/go-awesome-patterns)

repo can be used as a basic starter or reviewing of golang features

本仓库是Go语言基础,用来温习Go的常用套路或者作为入门学习.

all case was written by testing ,more story more cases

都以Test方式来写,方便直接测试,内容更加丰富,Test Case更加完善.

dowload 下载：

```go
go get github.com/crazybber/go-fucking-exercise
```

Test 测试：

```go
cd go-fucking-exercise
go test ./...
```

## Ways 姿势

逐个跑一遍或者敲一遍(可以直接COPY),但是要确保理解了，就可以丢一边了。


## current dir structure 当前目录结构

+ basic 基础类型
  + [Hello World](./basic)
  + [Values](./basic)
  + [Variables](./basic)
  + [Constants](./basic)
  + [For](./basic)
  + [If/Else](./basic)
  + [Switch](./basic)
  + [Arrays](./basic)
  + [Slices](./basic)
  + [Maps](./basic)
  + [Range](./basic)
  + [Functions](./basic)
  + [Multiple Return Values](./basic)
  + [Variadic Functions](./basic)
  + [Closures](./basic)
  + [Recursion](./basic)
  + [Pointers](./basic)
+ pattern go 的基本组合继承模式
  + [Structs](./patterns)
  + [Methods](./patterns)
  + [Interfaces](./patterns)
  + [Errors](.//patterns)
+ go routine 和Channels
  + [Goroutines](./routine)
  + [Channels](./routine)
  + [Channel Buffering](./routine)
  + [Channel Synchronization](./routine)
  + [Channel Directions](./routine)
  + [Select](./routine)
  + [Timeouts](./routine)
  + [Non-Blocking Channel Operations](./routine)
  + [Closing Channels](./routine)
  + [Range over Channels](./routine)
+ skill 常用套路
  + [Timers](./skill)
  + [Tickers](./skill)
  + [Stateful Goroutines](./skill)
  + [Sorting](./skill)
  + [Sorting by Functions](./skill)
  + [Panic](./skill)
  + [Defer](./skill)
  + [Collection Functions](./skill)
  + [String Functions](./skill)
  + [String Formatting](./skill)
  + [Regular Expressions](./skill)
  + [JSON](./skill)
  + [XML](./skill)
  + [Time](./skill)
  + [Epoch](./skill)
  + [Time Formatting / Parsing](./skill)
  + [Random Numbers](./skill)
  + [Number Parsing](./skill)
+ sync 同步相关
  + [Worker Pools](./snycs)
  + [WaitGroups](./snycs)
  + [Rate Limiting](./snycs)
  + [Atomic Counters](./snycs)
  + [Mutexes](./skill)
+ iostream 流相关，如文件流
  + [URL Parsing](./iostream)
  + [SHA1 Hashes](./iostream)
  + [Base64 Encoding](./iostream)
  + [Reading Files](./iostream)
  + [Writing Files](./iostream)
  + [Line Filters](./iostream)
  + [File Paths](./iostream)
  + [Directories](./iostream)
  + [Temporary Files and Directories](./iostream)
  + [Testing](./basic)
+ Command Lines
  + [Command-Line Arguments](./process)
  + [Command-Line Flags](./process)
  + [Command-Line Subcommands](./process)
+ process 进程相关
  + [Environment Variables](./process)
  + [Context](./process)
  + [Spawning Processes](./process)
  + [Executing Processes](./process)
  + [Signals](./process)
  + [Exit](./process)
+ Network 网络相关
  + [HTTP Clients](./network)
  + [HTTP Servers](./network)
+ attentions(一些坑)
  + [for range](./loops)
  + [for select break](./loops)
  + [deep copy](./more)
  + [slice append](./more)
+ misc 有用的杂项 
  + [Go文章](./misc/README.md)
  
## More 更多

learn go patterns by real example ?

想通过例子，学习一下go的常用的模式？看这里：

[Go模式(go-awesome-patterns)](https://github.com/crazybber/go-awesome-patterns)
