# 更新以下lab4b的代码 -- 2023.12.14
lab4b的代码是写完了，但是卡在了TestSnapshot测试上，组群重启后，shards数组的state成员都是Invalid状态（难道persister没有保存shards数组？？？），最大的槽点是太难调试了！！！只能看日志，简直是地狱级难度！！！，还是gdb香啊。以后有时间再调吧，感觉一两天很难肝完，最近真要被这个实验整崩溃了。

# 更新lab4b代码 -- 2023.12.15
搞定了昨天的bug跑通TestSnapshot。后续测试还是存在bug，待修复。