1、  src/test/java/com/alibaba/dubbo/rpc/demoservice is test provider consumer service
     src/test/java/com/alibaba/dubbo/rpc/gen/thrift is classes generated from idl files
     src/test/java/com/alibaba/dubbo/rpc/protocol/thrift is test case
     https://github.com/yankai913/dubbo-rpc-thrift
     https://github.com/leobasic/dubboPlus
     https://github.com/tianzhidao28/dubbo-thrift
     https://www.cnblogs.com/yjmyzz/p/dubbo-pritimive-thrift-avro-support.html
     https://github.com/yjmyzz/dubbox
     
  1）能dubbo框架内java项目互相调用，dubbo内的服务（不建议）
     其他语言的服务（客户端）能调用dubbo框架的服务
  同时兼顾
    1）attachment 传递 
    2）rpc跟踪 头传递数据
    3）dubbo admin dubbo 控制台监控