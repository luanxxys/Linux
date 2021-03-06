# top

### 通过 top 命令来查看 CPU 使用状况

    PID：进程的ID
    USER：进程所有者
    PR：进程的优先级别，越小越优先被执行
    NInice：值
    VIRT：进程占用的虚拟内存
    RES：进程占用的物理内存
    SHR：进程使用的共享内存
    S：进程的状态。S表示休眠，R表示正在运行，Z表示僵死状态，N表示该进程优先值为负数
    %CPU：进程占用CPU的使用率
    %MEM：进程使用的物理内存和总内存的百分比
    TIME+：该进程启动后占用的总的CPU时间，即占用CPU使用时间的累加值
    COMMAND：进程启动命令名称

### top 的全屏对话模式可分为3部分：系统信息栏、命令输入栏、进程列表栏

top 运行中可以通过 top 的内部命令对进程的显示方式进行控制。

内部命令如下表：

　　s - 改变画面更新频率
　　l - 关闭或开启第一部分第一行 top 信息的表示
　　t - 关闭或开启第一部分第二行 Tasks 和第三行 Cpus 信息的表示
　　m - 关闭或开启第一部分第四行 Mem 和 第五行 Swap 信息的表示
　　N - 以 PID 的大小的顺序排列表示进程列表（第三部分后述）
　　P - 以 CPU 占用率大小的顺序排列进程列表 （第三部分后述）
　　M - 以内存占用率大小的顺序排列进程列表 （第三部分后述）
　　h - 显示帮助
　　n - 设置在进程列表所显示进程的数量
　　q - 退出 top
　　s - 改变画面更新周期
