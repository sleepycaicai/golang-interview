# golang-interview

## Basic

- [defer关键字](https://tiancaiamao.gitbooks.io/go-internals/content/zh/03.4.html)
- interface的使用以及其底层实现
- function vs methods
- append
- 主要就是 slice的用法(创建方法)， slice和数组的联系和区别，slice底层的实现方式，还有一个空slice和nil的区别
- map的话你主要理解这几点就行了：1. map本省应该就是一个指针了 2. get方法是如何工作的，也就是如何根据key来找到value的，说出大致的过程就行 3. 怎么把key value对放到一个map里的   4. map不是线程安全的，那么线程安全的map应该怎么实现，大致原理是什么样的。



## Data structure

- slice
- map
- list
- heap
- stack vs queue
- tree 
- sort
- 常用算法
    - 二分查找
    - map统计出现次数
    - 数组用来统计出现次数
    - 简单的动态规划
    - 找规律解决问题
    - 字符串

## Concurrency

- 什么是并发
- 并发存在的问题
- go关键字
- select 
- channel
- sync包

## Web

- tcp http
- net/http中的mux
- rpc框架原理
    - 服务方，客户端，服务对象，编解码 这几个部分的作用 (https://www.zhihu.com/question/25536695)
    - net/rpc 
    - jsonrpc

## golang语法常见的坑

- [50 Shades of Go: Traps, Gotchas, and Common Mistakes for New Golang Devs](http://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/index.html)
