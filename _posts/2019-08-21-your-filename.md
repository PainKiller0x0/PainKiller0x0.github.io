---
published: true
title: 假设检验中的显著性水平
tag: study
---
## 统计学相关，假设检验知识点
   自己认真琢磨了一下发现是自己想歪了...被书里写的东西误导了

   以P检验为例
   
   假设A和B是互斥事件，即A发生了，那B必然不会发生
   
   然后，找到一个小概率事件X，X包含在A里面，那X的概率就为P（X）
   
   接着（关键！）设定一个显著性水平α，α一般为5%（0.05）或1%（0.01）
   
   此处的α可以理解成当前你可以接受的错误率，即你认为结果是A事件，但你也能接受有α的概率这个事件其实是B
   
   若P（X）＜α，说明在当前的容错率下，发生X事件是不可接受的，因此选择事件B
   
   若P（X）≥α，说明在当前的容错率下，发生X事件是正常的、可接受的，因此继续选择事件A
   
   思考题：
   
   你面前有两个箱子，A和B，但不知道两个箱子哪个是A，哪个是B
   
   已知A箱子里面有96个白球，4个黑球
   
   从面前的箱子里面抽出一个球，是黑球
   
   1）在显著性水平为5%时，判断箱子为哪个箱？
   
   2）在显著性水平为1%时，判断箱子为哪个箱？
   
   3）在2的前提下，把取出的黑球再放进去，然后再从箱子里面取一个球，结果还是黑球，此时判断箱子为哪个箱？


参考文献： 
	
   <a href="https://blog.csdn.net/shenxiaoming77/article/details/51452012" target="_blank">https://blog.csdn.net/shenxiaoming77/article/details/51452012</a>
   
   <a href="https://www.zhihu.com/question/31615254" target="_blank">https://www.zhihu.com/question/31615254</a>
   
   <a href="https://www.jianshu.com/p/aca87a78e134" target="_blank">https://www.jianshu.com/p/aca87a78e134</a>
