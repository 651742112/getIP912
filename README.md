# getIP912
运行环境：Win10、Win7系统，不需要依赖插件
编程语言：Python3.6+PyQT5
功能：
1. 软件第一次启动。建立配置文件，配置文件的参数与默认值为，‘autoLogin’=True、‘remberPassword’=False、’username’=’’、’password’=’’。修改系统注册表，实现开机自启。
2. 可以通过用户名和密码登陆到服务器。如果用户名和密码错误，则登陆失败并提示，参数‘isLogin’=False。如果用户名和密码正确，则登陆成功，参数‘isLogin’=True；同时，如果用户选择了‘remember’,并且登陆成功，则更新配置文件的参数。
3. 软件再次启动时，若’remberPassword’=True,自动填充用户名和密码。若’autoLogin’=
True，自动登陆，系统默认参数’autoLogin’为True，用户不可更改。
4. 在软件启动后，用户未登陆且参数’remember’=True，则间隔15秒查看登陆状态。若未登陆，则自动登陆一次。若已登陆，则检测是否有连不上服务器的情况，当连不上服务器时退出登陆。
5. 用户登陆成功后，间隔2秒向服务器发送主机的外网IP地址和用户名、mac地址。

使用：
1.下载软件即可自动获取外网地址并上传到服务器。
2.请使用账户：test 密码：test
3.登陆 www.37300.top，查看自己电脑IP地址







































