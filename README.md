# gitNotebook
记录关于git使用中的经验

---------------------------------------------------
2022/09/11 
In China Suzhou
当上传本地文件时，出现如下错误：
 OpenSSL SSL_read: Connection was reset, errno 10054
 
 可以使用下记方法：
 取消SSL的认证
 git config --global http.sslVerify "false"
 
 让后使用git init 初始化
 
 以上方法测试有效。
 -------------------------------------------
 
