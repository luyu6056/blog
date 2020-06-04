# blog
这是一个用go作为后端的开发的博客，预计采用双端渲染（首次请求后端渲染+二次请求api前端渲染）

采用来自[@panjf2000](https://github.com/panjf2000/gnet)的gnet，再加上我为其开发的[tls，http2,ws解码器](https://github.com/luyu6056/gnet)，作为协议层框架，由于是后端渲染，所以不可避免的采用了mvc结构
