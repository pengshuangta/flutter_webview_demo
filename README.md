# flutter_webview_demo
一个flutter_webview交互的demo，主要用的插件是：webview_flutter 0.3.9+1
# demo内容：
1、webview的简单使用，加载一个百度地址；  
2、js调用flutter的两种方式：（1）javascriptChannels发送消息 （2）navigationDelegate拦截url；（注：javascriptChannel的方法，如果很多可以让h5端采用json字符串的方式包含一个字典map，然后本地客户端在收到json字符串在转成map，然后生成model，方便扩展）  
3、flutter调用js：简单的做了一下监听网页的标题，document.title；  
4、[参考链接一](https://www.jianshu.com/p/2c721bf5f6e1)，[参考链接二](https://www.jianshu.com/p/4aabe453eb26)，

