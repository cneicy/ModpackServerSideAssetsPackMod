# ModpackServerSideLanguageFix
修复服务端传输国际化文本到客户端接收到的是raw的langkey的解决方案。

（翻译：在服务器的玩家会直接收到一条原始的langkey,而不是langkey的消息。）


原理为直接使用模组特性加载lang文件。

TODO：

  读取文件自动设置langkey。
  
