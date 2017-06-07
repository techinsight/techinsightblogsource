
在Android中获取**运行进程**这种需求在许多场合需要被使用到，但实际情况是在Android Lollipop即5.0后，Google开始收紧对底层权限控制。开始对某些原有方法的返回进行修改，类似[getRunningAppProcesses()](https://developer.android.com/reference/android/app/ActivityManager.html#getRunningAppProcesses())在直到4.x版本上工作良好（即便API中提示此方法仅用于debugging及编译管理UI之用），但从5.0开始在一些OEM的系统中调用此方法进行测试会发现方法返回null。

TO BE CONTINUED ......