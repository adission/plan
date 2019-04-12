#### 本文主要配置mac上python3环境，用以备忘
##### 一般来说，我们ma命令行输入python，默认调用的python2版本，目前很多库python2已经不再支持维护。重点还是使用python3，下面我们开始配置。

+ 安装完毕python3以后，敲入命令 which python，安装路径为：
```
/Library/Frameworks/Python.framework/Versions/3.6/bin/python3
```
+ 我们将这个路径配入环境变量 vim ~/.bash_profile  -- 最后面加入下面这行
```
alias python="/Library/Frameworks/Python.framework/Versions/3.6/bin/python3.6"
```

+ 保存好后执行 source ~/.bash_profile 或者重启电脑。