#<center>**小学生四则运算测试系统软件需求文档**</center>

***
<br />
##1. 引言
###1.1 目的
&emsp;&emsp;本文档描述了小学生四则运算测试系统的软件需求规格。目的在于向读者表述系统的环境，系统的功能和非功能的需求。
###1.2背景
&emsp;&emsp;名称：小学生四则运算测试系统。

&emsp;&emsp;项目提出者：Teacher

&emsp;&emsp;项目开发者：Hahalovejava团队

&emsp;&emsp;用户：通过小学生四则运算测试系统来进行测试的人

&emsp;&emsp;本次软件项目开发的是一个小学生四则运算测试系统。使用此系统的用户通过此系统进行小学生四则运算的练习。系统的功能如下：

&emsp;&emsp;*用户能够通过本系统进行注册账号。

&emsp;&emsp;*用户能够通过本系统进行登陆账号。

&emsp;&emsp;*用户能够通过本系统进行四则运算练习，包括简单四则运算、混合四则运算、真分数四则运算。

&emsp;&emsp;*用户能够通过登录本系统，填写题目答案，取得相应分数。

&emsp;&emsp;*用户能够通过登录本系统，查看做题的得分记录、用时等信息。

&emsp;&emsp;*用户答错的题目可以显示正确答案。
###1.3 术语
&emsp;&emsp;真分数：真分数就是分子小于分母的分数，我们把这样的分数叫做真分数。

&emsp;&emsp;简单四则运算：表达式只含 +, -, *, / 四则运算符中的某一个，不含括号。

&emsp;&emsp;混合四则运算：同级运算时，从左到右依次计算；两级运算时，先算乘除，后算加减。有括号时，先算括号里面的，再算括号外面的；有多层括号时，先算小括号里的，再算中括号里面的，最后算括号外面的。要是有乘方，最先算乘方。在混合运算中，先算括号内的数 ，括号从小到大，如有乘方先算乘方，然后从高级到低级。
##2.系统需求概述
###2.1 用例模型
&emsp;&emsp;系统用例图如下：

![](http://i.imgur.com/TkKA8Pg.png)

用例的概要描述如下表所示：
<table>
 <tr>
   <td>主要参与者</td>
   <td>优先级</td>
   <td>用例名</td>
   <td>用例概述</td>
 </tr>
 <tr>
   <td>用户</td>
   <td>高</td>
   <td>注册账号</td>
   <td>用户打开系统后，可以点击“点此注册”按钮，注册新的账号，且不能与现有账号名相同。</td>
 </tr>
 <tr>
   <td>用户</td>
   <td>高</td>
   <td>登陆账号</td>
   <td>用户可以使用在本系统注册的账号和密码进行登录，然后才能使用系统的完整功能。</td>
 </tr>
 <tr>
   <td>用户</td>
   <td>高</td>
   <td>查看得分记录</td>
   <td>用户成功登录系统之后，可以查看自己的得分记录，包括时间、用时、得分。</td>
 </tr>
 <tr>
   <td>用户</td>
   <td>高</td>
   <td>进行练习</td>
   <td>用户成功登录系统之后，可以选择相应的类别进行做题练习，包括简单四则运算、混合运算、真分数运算。每次20题，每题1分。</td>
 </tr>
 </table>
 
 
 ###孙雪莹change
 ###原旭莹change
