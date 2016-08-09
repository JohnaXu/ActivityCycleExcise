# ActivityCycleExcise

根据郭霖的《android第一行代码》写的关于activity的练习。主要包括生命周期与启动模式。
standard:每启动一个新活动，新活动就会在返回栈中入栈毛病处于栈顶位置；
singletop:启动活动时如果发现返回栈栈顶已经是该活动，则直接使用该活动，不再创建新的活动实例；
singletask:每次启动活动时，检查返回栈是否有该活动，如果有，直接启动不创建新活动实例；
singleInstance:有一个单独的返回栈管理这个活动，解决活动共享问题