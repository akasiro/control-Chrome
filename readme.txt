1、打开一个chrome
在命令行中输入
C:\Users\ruc_c>chrome.exe --remote-debugging-port=9222 --user-data-dir="C:\Users\ruc_c\AppData\Local\Programs\Python\Python36-32\Lib\site-packages\selenium"

/**
注
对于-remote-debugging-port值，可以指定任何打开的端口。
对于-user-data-dir标记，指定创建新Chrome配置文件的目录。它是为了确保在单独的配置文件中启动chrome，不会污染你的默认配置文件。
还有，不要忘了在环境变量中PATH里将chrome的路径添加进去。

**/

2、运行代码接管浏览器


参考文献
中文
https://www.cnblogs.com/lovealways/p/9813059.html
英文
http://www.teachmeselenium.com/2018/08/11/how-to-connect-selenium-to-an-existing-browser-that-was-opened-manually/


