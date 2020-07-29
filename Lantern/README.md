# 蓝灯启动后有可能会报错“无法设置系统代理”

## 检测方法：

在系统设置——手动代理中随意输入，查看是否会保存设置

## 处理方法:

第一步：先关闭退出蓝灯

第二步：双击打开注册表文件，文件路径复制即可访问C:\Windows\regedit.exe

第三步：找到HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Internet Settings\Connections这项表全部删除即可