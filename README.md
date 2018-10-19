
该项目用于netty的handler模块，主要提供利用openssl进行SSL通信的功能，为了支持国密SSL，我们在其中进行了以下修改:
* 使用支持国密协议的openssl替换原生的官方openssl
* 编译时不再从官方下载openssl
* 修改Java文件以及对应的JNI文件，增加设置国密SSL参数的调用接口
* 更加详细的内容，请查看Git或者SVN的提交日志
