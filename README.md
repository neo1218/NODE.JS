# NODE.JS

    my node.js study repo [funny fucking node!]

[video: node.js 视频资源](https://github.com/neo1218/NODE.JS/tree/master/Video)  [blogs: node.js 相关博客](https://github.com/neo1218/NODE.JS/tree/master/Blogs) <br/>
[hackers: node.js 界的大神们](https://github.com/neo1218/NODE.JS/tree/master/Hackers)
<hr/>
[stream notebook 笔记](https://github.com/neo1218/NODE.JS/tree/master/stream)
<hr/>
## node.js 究竟是什么?
http://www.ibm.com/developerworks/cn/opensource/os-nodejs/index.html?ca=drs#ibm-pcon

## My Node Code
### hello-world.js

    hello from js
    从这个简单的helloworld代码里可以看出js的一个很重要的编程思想
    面向事件编程(envents driven)

### hello-world2.js

    hello from js but setInternal
    有意思的是可以在world持续输出的过程中输入别的东东
    而不终止程序(别输Ctrl-c)

### simpleServer.js

    node 实现的简单的服务器
    监听 3000 端口, 回调函数接受request, 处理response回调

### TCPServer.js

    node 实现TCP服务器, 使用 Transform-Encoding: chunked
    分块编码
    但是: 我这里并没有解决持久连接呀!!!!!

### genNum.js

    简单的 node 随机数生成器
