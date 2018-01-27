### 让git的提交可以使用emoji表情

- 初始化提交- :taba:
- [一篇整体配置git emoji的简易教程](https://mp.weixin.qq.com/s?__biz=MzU0OTE3MjE1Mw==&mid=2247483777&idx=1&sn=dec9764fbb1307cb2b6af4c3a540004c&chksm=fbb2a757ccc52e41459d887b3e6306b3b7a1466cbcdb31f784bef9e3e038993d32a8cebcec2d#rd)
- 使用gitmoji-cli简化每次提交都要手动输入
    - [gitmoji-cli](https://github.com/carloscuesta/gitmoji-cli)
- gitmoji-cli的提交需要开启GPG验证，有关gpg的文章
    - [使用GPG签名commit](https://www.cnblogs.com/xueweihan/p/5430451.html) 2016年的文章，流程上具有一定参考性，命令有些不适用
    - [GitHub GPG配置](http://blog.csdn.net/faremax/article/details/71981601) 2017年的文章，基本可以参考配置
    - [GitHub GPG配置](http://blog.csdn.net/everblog/article/details/79032868) 比较简洁的一篇文章
    - [GitHub官网配置教程](https://help.github.com/articles/generating-a-new-gpg-key/)
    - 关于GPG加密的几篇文章
        - [http://www.ruanyifeng.com/blog/2013/07/gpg.html](http://www.ruanyifeng.com/blog/2013/07/gpg.html)
        - [http://blog.csdn.net/ppw001/article/details/44928715](http://blog.csdn.net/ppw001/article/details/44928715)
        - [http://www.linuxidc.com/Linux/2015-02/113015.htm](http://www.linuxidc.com/Linux/2015-02/113015.htm)
    - [error: gpg failed to sign the data错误的处理](https://stackoverflow.com/questions/41052538/git-error-gpg-failed-to-sign-data)
        - 这个错误很诡异，解决多次无果后，重启了下电脑就没问题了... 万能的重启...
- gitmoji表情的说明
    - [en](https://gitmoji.carloscuesta.me/)
    - [zh](http://gitmoji.surge.sh/)