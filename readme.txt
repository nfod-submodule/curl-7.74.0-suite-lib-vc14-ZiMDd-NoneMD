静态库，在Visual Studio 2015环境下编译

调试版：
    调试信息格式(Debug Information Format)：程序数据库(/Zi)
    运行库(Runtime Library)：多线程调试DLL(/MDd)
发布版：
    调试信息格式(Debug Information Format)：无
    运行库(Runtime Library)：多线程DLL(/MD)

curl-7.74.0
https://curl.se/
https://curl.se/download/curl-7.74.0.tar.gz
https://github.com/curl/curl.git

libssh2-1.9.0
https://www.libssh2.org/
https://www.libssh2.org/download/libssh2-1.9.0.tar.gz
https://github.com/libssh2/libssh2.git

openssl-1.1.1i
https://www.openssl.org/
https://www.openssl.org/source/old/1.1.1/openssl-1.1.1i.tar.gz
https://github.com/openssl/openssl.git

zlib-1.2.11
http://zlib.net/
http://zlib.net/zlib-1.2.11.tar.gz
https://github.com/madler/zlib.git

使用说明
	1. 引用此静态库须添加预处理器定义：CURL_STATICLIB
	   (中文) 配置属性 -> C/C++ -> 预处理器 -> 预处理器定义
	   (English) Configuration Properties -> C/C++ -> Preprocessor -> Preprocessor Definitions
