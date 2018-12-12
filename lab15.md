# 智能蛇实验报告
程序代码在该网站下     
https://github.com/xukangze123/test-repo       
在上周作业后，参考了别人的代码。在贪吃蛇的基础上使它自己吃食物，              
![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/BL0hkbmw4W9RP0vTKL8xoc8kccmqjHNwiCc4raqBDKk!/b/dDYBAAAAAAAA&bo=egORAQAAAAADB8s!&rf=viewer_4)             
这是使得蛇能够自己寻找食物的伪代码           
![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/14iMBbnqgTeqMlQmm7m6jMpFStOkz4*DFYfYzDrgBDU!/b/dL0AAAAAAAAA&bo=mQRcAgAAAAABB.M!&rf=viewer_4)          
这是使得蛇移动的的代码      
但是由于此算法是使蛇仅仅考虑最短路径而去吃食物，所以该蛇还是会很容易的自己把自己困住从而死亡。      
![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/945H0LtOOwGdo4UBpRlRDjD2JG65iVaD7AKyEC9fCOM!/b/dLYAAAAAAAAA&bo=RQJYAQAAAAADBzw!&rf=viewer_4)      
在网上参考了别人的算法后，我发现有一种算法是引入了评分机制——即对蛇行走的四个方向进行评分。选择分数较高的那条路进行行走。        
![image](http://m.qpic.cn/psb?/V11lkfIM05bhcV/r5ky0iIM.9KJ1ixusB8.2mnmBR3MBqn2lGFY3N0lo4I!/b/dLkAAAAAAAAA&bo=LQSUAQAAAAADB54!&rf=viewer_4)      
这是该大佬的评分标准        
通过对不同的算法进行对比，我感悟到了进行设计时选择合适的算法的重要性。        