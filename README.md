# 项目名称
sm3_BirthdayAttack
# 项目简介
生日攻击不是真实的一个攻击，而是一种概率的结果。生日攻击是以概率论中的生日问题为数据基础的一种密码学攻击方法。由于是属于暴力穷举的一种，所以它能对任何类型的散列函数进行攻击。
# 完成人
何静
# 项目流程
选择碰撞前n比特

暴力穷举
# 部分代码说明
整体还是依靠之前实现过的sm3算法

string SM3(string message)——代执行sm3加密过程
# 运行过程截图
碰撞的前n bit（n需要输入)

![image](https://user-images.githubusercontent.com/104714591/181275682-3c519c2e-505e-48bd-a3a8-3e3a69b7df18.png)
# 引用参考
[1]https://blog.csdn.net/superfjj/article/details/117729922?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-1-117729922-blog-104206696.pc_relevant_vip_default&spm=1001.2101.3001.4242.1&utm_relevant_index=4
[2]https://blog.csdn.net/weixin_43749051/article/details/104206696?utm_medium=distribute.pc_relevant.none-task-blog-2~default~baidujs_baidulandingword~default-2-104206696-blog-117729922.pc_relevant_vip_default&spm=1001.2101.3001.4242.2&utm_relevant_index=5
[3]https://blog.csdn.net/ddk3001/article/details/52647990

