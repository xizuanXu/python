测试
1 将github中的仓库拷贝到本地
   1.1 openssl ssl_read:connection was reset,errno 10054
         1.1.1 输入 git config --global http.sslVerify "false",解除SSL验证
         1.1.2 将地址https://改为git://,避开SSL验证