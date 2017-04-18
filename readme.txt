使用方法：
1、直接使用浏览器打开login.html即可查看
2、大写监听绑定在密码输入框

实现方法：
1、将大写提示封装为接受一个参数的function，接受参数为需要提示大写提示的输入框的id

目录结构：
1、代码比较简单，所以将关键代码都在login.html中：
    文件中的style是大写提示的样式；
    文件中的script中的capitalTip是封装的显示大写的function；
2、imgs里是大写提示div的背景图片；
3、css通用为bootstrap样式；
4、js是公用的jQuery及bootstrap的js文件。