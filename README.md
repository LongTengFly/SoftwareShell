# SoftwareShell
Anthoer Resurce
# 使用说明
or
## 一、前因

在Memory测试过程中，需要使用大量的测试软件对其进行测试，以保证Memory的良品。在Windows下，每个测试软件都是单独操作测试，耗时耗力，因此，为了减少不必要的时间浪费以及人力成本，开发出具有自动监控测试软件的软体极为重要。
## 二、使用环境

Windows10、Windows7
## 三、支持测试软件
1、BurinTest V8.1
2、3DMark V2
3、StartMemTest  V1.0.0
4、Sleeper V2.3
5、rebooter V1.3
## 四、准备工作
将Windows账户控制权限设置为最低，以达到自动开启需要管理员权限的测试软件（如BunrinTest V8.1），具体步骤如下。

首先，右击“我电脑”，点击“属性”；

其次，点击底部的“安全与维护”；

最后，点击“更改用户账户控制设置”，将通知设为“从不通知”，点击“确定”即可。
## 五、操作说明
1、在基本设置界面选中测试软件，通过“置顶、上移、下移、移除、重置”按钮设置测试软件的启动优先级；

2、在基本设置界面选中测试软件，通过“设置参数”按钮设置测试软件的相关参数。勾选“Rebooter”则在所有测试软件测试结束后，将启动rebooter测试软件作为最后的测试。

3、点击“开始测试”，程序开始启动测试软件，并对整个过程进行监控；下一个测试软件将进行15S计时结束后启动。

4、测试软件的测试结果保存在LogFile文件夹下，包括log及截图；

5、使用总结：优先级设置，参数设置，开始监控。
## 六、建议
每次测试结束后，建议将LogFile中的文件拷贝到个人文件，以便进行测试报告的书写。
