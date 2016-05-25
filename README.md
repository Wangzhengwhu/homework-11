# homework-11
##多星系统运动轨迹 
##摘要
介绍了太阳系的行星运动的轨迹。行星运动的轨迹与在地球上不同，不需考虑空气阻力的影响，一般来说只需考虑引力作用，它们之间的力与距离的平方成反比。一般来说，它们的运动轨迹会有椭圆、抛物线、和双曲线三种，依据初始条件给定。因而从万有引力定律出发，研究双星系统运动的轨迹。
##正文
由牛顿的万有引力方程，我们可以得出太阳系中的引力关系式如下  
![](https://github.com/Wangzhengwhu/homework-11/blob/master/%E5%85%AC%E5%BC%8F1.png)  
联立牛顿第二定律给出行星运动的轨迹。考虑太阳的有效质量，行星运动的二体问题也可解决，只需引入折合质量，u，解决行星的运动问题。  
折合质量可表示为  
![](https://github.com/Wangzhengwhu/homework-11/blob/master/%E5%85%AC%E5%BC%8F2.png)  
通过积分我们可以求出行星运动的轨道方程  
![](https://github.com/Wangzhengwhu/homework-11/blob/master/%E5%85%AC%E5%BC%8F3.png)  
其中，l为  
![](https://github.com/Wangzhengwhu/homework-11/blob/master/%E5%85%AC%E5%BC%8F4.png)  
e是轨道的离心率，如果0<e<1,为椭圆轨道，e=1为抛物线，e>1为双曲轨迹，这方程的前提条件是万有引力大小严格的与距离的平方成反比，如果有微小的偏差，那么轨迹讲不满足以上的圆锥曲线，一般来讲不会闭合。  
###双星问题
双星系统课通过前面的操作变可为单星系统，接下来我们来给出双星系统的运动轨迹   
[程序](https://github.com/Wangzhengwhu/homework-11/blob/master/1.py)  
![](https://github.com/Wangzhengwhu/homework-11/blob/master/%E5%9B%BE1.png)  
图中所给的质量满足M1/M2=2，在不同的初始条件下，我们可以看出双星运动的轨迹完全不同。在一定条件下可以形成圆形，在另一条件下，轨迹是椭圆，单都可以稳定的运行下来，稳定性较好。
###万有引力不严格满足平方反比
如果万有引力不严格满足平方反比的条件下，运动轨迹会发生一些变化，比如会产生进动现象，水星的运动，他们每转一圈会转过一定的角度。满足的方程为  
![](https://github.com/Wangzhengwhu/homework-11/blob/master/%E5%85%AC%E5%BC%8F5.png)  
其中a不为2。接下来给出在不同初始条件下的行星运动的轨迹  
[程序](https://github.com/Wangzhengwhu/homework-11/blob/master/2.py)  
![](https://github.com/Wangzhengwhu/homework-11/blob/master/%E5%9B%BE2.png)  
上图展示了a=2.05时的情况，认为中心天体不动。图(a)展示了初始条件合适时，行星仍然能够保持圆轨道运动，此时不发生进动。而图(b)(c)则展示了行星轨道偏离圆周运动时，轨道将不是闭合的椭圆，而是不断进动，离心率越大时，进动越明显。图(d)给出了进动速率随离心率变化的规律。
![](https://github.com/Wangzhengwhu/homework-11/blob/master/%E5%9B%BE3.png)  
上图展示了a=1.95时的情况，认为中心天体不动。图(a)展示了初始条件合适时，行星仍然能够保持圆轨道运动，此时不发生进动。而图(b)(c)则展示了行星轨道偏离圆周运动时，轨道将不是闭合的椭圆，而是不断进动，离心率越大时，进动越明显。图(d)给出了进动速率随离心率变化的规律。

##结论 

##致谢
感谢陈洋遥同学提供的帮助

