# ETcpPlugin
 
1. 魔改了一下[原始项目](https://github.com/CodeSpartan/UE4TcpSocketPlugin)
2. 上层业务就不用自己做内存拷贝了
3. 提供简单的重连功能
4. 提供高效的缓存功能，线程运行方式也调整，全异步socket api调用
5. 测试无泄漏
6. [例子](https://github.com/DAN-AND-DNA/ETcpPlugin/blob/main/Source/ETcpPlugin/Private/ETcpConnection.cpp)
7. [参考项目](https://github.com/DAN-AND-DNA/TopDownSoulsLike)

## 图片
![connect](/imgs/connect.png)
![request](/imgs/request.png)