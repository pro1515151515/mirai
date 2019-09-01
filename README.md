# Mirai

一个以<b>TIM QQ协议</b>驱动的JAVA(+Kotlin) QQ机器人服务端核心  
我们坚持免费与开源  
  
项目处于快速开发阶段, 现在已经可以接受和发送群聊/好友消息. 
协议来自网络上开源项目
一切开发旨在学习, 请勿用于非法用途  

<br>

A JAVA(+Kotlin) powered open-source project under GPL license<br>
It use protocols from <i>TIM QQ</i>, that is, it won't be affected by the close of <i>Smart QQ</i><br>
The project is all for <b>learning proposes</b> and still in <b>developing stage</b><br>

### 代码结构
Network部分使用 Kotlin 完成(因为kt有对 unsigned byte 的支持).
与插件相关性强(或其他在二次开发中容易接触的部分)均使用 Java 完成, 
同时也会针对kotlin提供优化的方法调用. 例如对'+'操作符的重载: `String+BufferedImage+QQ.At+Face+URL+String+File` 将会被自动处理为String消息.


### TODO
- [x] 事件(Event)模块  
- [ ] 插件(Plugin)模块 **(Working on)**  
- [x] Network - Touch  
- [X] Network - Login 
- [X] Network - Session
- [ ] Network - Verification Code (Low priority)
- [X] Network - Message Receiving
- [X] Network - Message Sending
- [ ] Network - Events **(Working on)**  
- [ ] Robot - Friend/group list
- [ ] Message Section **(Working on)**
- [ ] Contact

<br>

## 使用方法
### 要求
- Java 11 或更高
- Kotlin 1.3 或更高
### 插件开发
``` php
    to be continued
    ...
```


## Usage
### Requirements
- Java 11 or higher
- Kotlin 1.3 or higher
### Plugin Development
``` php
    to be continued
    ...
```




