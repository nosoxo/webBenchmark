# web基准测试
http基准测试工具可以耗尽服务器带宽。
- 每个请求都有随机的用户代理
- 可定制的引荐来源网址
- 您希望的并发线程取决于您的服务器性能。

# 用法: 
    webBenchmark -c [COUNT] -s [URL] -r [REFERER]
    -c int
          cocurrent thread for download (default 8)
    -r string
          referer url
    -s string
          target url (default "https://baidu.com")

# LINUX:
    wget https://github.com/nosoxo/webBenchmark/releases/download/0.1/webBenchmark_linux_x64
    chmod +x webBenchmark_linux_x64
    ./webBenchmark_linux_x64 -c 32 -s https://target.url

