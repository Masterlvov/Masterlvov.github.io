# Github主页无法推送的解决办法"

咸蛋超学锁:
检查ping不ping得通GitHub

咸蛋超学锁:
ping得通之后去检查公钥和私钥

咸蛋超学锁:
有问题的话重置，而且编码格式的注意

咸蛋超学锁:
[图片]

咸蛋超学锁:
出现这个因为公钥加密格式可能不一样

咸蛋超学锁:
需要添加known_hosts文件

咸蛋超学锁:
[图片]

咸蛋超学锁:
The authenticity of host 'github.com (140.82.112.3)' can't be established. ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU. This key is not known by any other names Are you sure you want to continue connecting (yes/no/[fingerprint])? Host key verification failed.就是这个错误

咸蛋超学锁:
ping不同需要去查找GitHub的ip，修改host文件

咸蛋超学锁:
[图片]

咸蛋超学锁:
还是显示没权限的话

咸蛋超学锁:
可能是服务器的和本地的发生冲突了

咸蛋超学锁:
hint: Updates were rejected because the remote contains work that you do hint: not have locally. This is usually caused by another repository pushing hint: to the same ref. You may want to first integrate the remote changes hint: (e.g., 'git pull ...') before pushing again. hint: See the 'Note about fast-forwards' in 'git push --help' for details.这种错误

咸蛋超学锁:
https://blog.csdn.net/qq_54000767/article/details/133190968参见这篇博客

咸蛋超学锁:
https://gitee.com/if-the-wind/github-hosts

咸蛋超学锁:
https://blog.csdn.net/qq_45677671/article/details/118905658 下一步操作看这个

