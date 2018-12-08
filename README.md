# ZitieMaker
字帖生成程序，用于打印字体，练习汉字


使用方式：按页面提示输入文字，点击生成字帖之后，通过预览界面可以打印。。。当然还需要一台打印机，主要是可以选择自己喜欢的字帖，和自定义文字
可以通知此地址访问：[http://zitie.leanapp.cn](http://zitie.leanapp.cn)

效果图：
![字帖效果图](http://lc-wdxn9gtr.cn-n1.lcfile.com/aa8958b14c19656bb578.jpg =300)

空白字帖效果图：
![空白字帖图](http://lc-wdxn9gtr.cn-n1.lcfile.com/66be2ecd4ae9f9269bbc.jpg =300)

主要代码在 public/index.html 里面
fork了 [https://github.com/kinders/chinese-copybook-maker](https://github.com/kinders/chinese-copybook-maker) 的代码，并修改了逻辑代码。
原来的功能：
1. 输入文字输出字帖
2. 字体选择等...

增加的功能：
 1. 增加了对换行符号的处理，可以处理多行文字了
 2. 增加了行数、列数的控制，方便打印
 3. 增加了空白网格的功能，可以打印空白字帖
 4. 增加了对高清屏幕的支持

修改了部分界面

ToDo：
 1. 没有在windows上进行测试。
 2. 目前只支持小篇幅文字，大篇幅未测试。
 3. 目前只支持汉字，英文未支持。
 4. 虚线有点问题，待修复。