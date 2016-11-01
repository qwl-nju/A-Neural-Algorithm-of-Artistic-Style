一、关于caffe的python接口配置
1用acconda安装python 并下载相应的包
2编译的时候要用好reslse模式，否则提示缺少Python27文件
3在VC++目录中添加各种路径，否则报错，提示找不到头文件，无法编译
4主要参考：
http://www.bubuko.com/infodetail-1771113.html
https://zhidao.baidu.com/question/2013535837382668908.html


二、文件的运行（文件中包含pycaffe不需要自己重复复杂的编译过程）
1下载https://github.com/fzliu/style-transfer的文件
2下载VGG19的模型放入model对应文件夹
3将本件夹里的pycaffe文件件内的文件复制到python的site-packages中，这样在任何地方打开import caffe都是可以的
4进入anaconda-prompt将新建.txt文件中的命令复制运行，其中的路径改为自己的实际路径。# A-Neural-Algorithm-of-Artistic-Style
