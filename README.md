[![Documentation Status](https://readthedocs.org/projects/sanic-for-pythoner/badge/?version=latest)](http://sanic-for-pythoner.readthedocs.io/zh_CN/latest)

## Sanic-For-Pythoner

> 这是一份记录文档，是我日常对`Sanic`使用过程中一些问题的记录
>
> 虽说是大杂烩，但我也会尽量使其连贯，或许能使一些人在使用Sanic的过程中少走一些弯路
>
> 可根据需求跳跃阅读，在线[地址](http://sanic-for-pythoner.readthedocs.io/zh_CN/latest)

### 1.介绍

**Sanic**是一个可以使用 `async/await` 语法编写项目的异步非阻塞框架，它写法类似于`Flask` ，但使用了异步特性，而且还使用 `uvloop` 作为事件循环，其底层使用的是**libuv**，从而使 `Sanic` 的速度优势更加明显

我于2017年2月份就开始使用 `Sanic`，使用过程中确实遇到不少问题，如缓存、模板引入、session、认证...

但不用担心，`Sanic` 更新速度非常快，许多问题都在逐步地解决中，并且比同类别更出色更优秀，个人觉得 `Sanic` 是一个值得尝试的异步框架，不论是代码编写还是性能比较都算非常不错

本项目的结构如下：

**第一部分：**

- [x] [1.初使用](./docs/part1/1.初使用.md) 			
- [x] [2.配置](./docs/part1/2.配置.md)             
- [x] [3.项目结构](./docs/part1/3.项目结构.md)
- [ ] [4.展示一个页面](./docs/part1/4.展示一个页面.md)
    - 视图
    - 路由
    - 模板
    - 静态文件
    - 蓝图
- [ ] [5.数据库使用](./docs/part1/5.数据库使用.md)
    - mysql
    - mongodb
    - redis
- [ ] [6.常用的技巧](./docs/part1/6.常用的技巧.md)
    - 接口验证
    - session
    - 缓存
- [ ] [7.安全问题](./docs/part1/7.安全问题.md)
    - csrf
- [ ] [8.可靠的拓展](./docs/part1/8.可靠的拓展.md)
- [ ] [9.测试与部署](./docs/part1/9.测试与部署.md)


### 2.更新

代码的世界变幻莫测，我能做的就是尽量将本篇文档持续更新、持续修正、让其处于当前最新的状态
