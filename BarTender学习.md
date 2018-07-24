##  BarTender学习 (2018.07.24)
* [BarTender 制作条形码的经典案例](http://www.bartender.cc/jingdiananli/)
1. `去BarTender的官网下载使用版的BarTender`
2. `完整安装BarTender`
3. `在BarTender进行数据库设置导入的时候报office是32位的解决措施`
```
* 微软官网下载 AccessDatabaseEngine_X64.exe
* cmd
* "C:\directory path\AccessDatabaseEngine_x64.exe" /passive
* cmd -> input  regedit , 打开注册表
* 删除 mso.dll  HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Office\14.0\Common\FilesPaths，删除mso.dll
```
* [在64位Win7操作系统中安装Microsoft Access Engine的解决方案](https://blog.csdn.net/sundacheng1989/article/details/17925431)
4. `重启BarTender即可使用数据库的功能`