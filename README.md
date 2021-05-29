### Author:zhaole
### github：https://github.com/colorfulchn
### QQ：384113120
### Email:lezhaochn@gmail.com

//欢迎一起讨论具体。github会在实验结束时间附近上传。^_^
//近期较忙，可能不能及时回复～

1、运行前说明
由于本代码对于选项的选择的设计是char类型，并不是string，所以尽量输入单键，如果要在windows下编译该代码，要将程序中system(“clear”)改为system（“cls”），OS X则不用，则是因为在linux/类unix的系统下terminal指令和windows下cmd的指令不一样，但是不影响程序的功能性实现，但是会影响人机交互界面的友好性。基于的c++版本是c++11，可以往最新版本兼容，旧版本没有进行测试。

2、在linux下的运行
在terminal找到a.cpp（我的代码）所在的路径，我放在桌面上的cpp文件里，由于我自己的电脑上是clang，所以用的是clang++，而在远程平台上，用
g++ a.cpp -o a.o -std=c++11,
并且在编译无误以后，运行a.o
./a.o

3、主界面的进入
键入功能字母按回车进入对应功能

4、创建多项式的输入
按照系数和幂次的顺序输入每一项，并且以#结尾。例如：X3+3X2+2X+6,我们输入1 3 3 2 2 1 6 0 #

5、保存与否
保存键入1，后回车。不保存键入0，后回车。

6、求和、乘法的index输入
以-1为结尾，比如求index为0、1、2、0这四项的和和乘法结果：
键入0 1 2 0 -1后回车

7、删除的index输入
以-1结尾，一个一个删除，比如要删除的index为2，则：
键入0 -1后回车

8、返回主界面
键入任意单个键按回车，比如：
键入b后回车。
