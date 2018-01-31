一切都是从碰到困难开始的……

萌生写一本有关Luna的Cookbook的想法时，实话说，感觉Luna真是前途未卜。

**涉及到密码的要么是luna要么是luna-lang.cn，不要慌。**

# 可恶的墙

## 安装

### 在线安装
- [LunaInstaller][0]

- luna-manager install
  - C:\Users\bob\AppData\Local\Programs\stack\x86_64-windows
  - C:\sr
  - C:\LunaStudio\1.0\bin\public\luna-studio

### 离线安装
- [LunaStudioV1.0beta][1]

网络好、速度快的朋友可以跳过，本小节针对墙内群众。

	用网络监控工具查看LunaInstaller进程，会发现在线安装LunaStudio的下载路径：https://d1uis3r8vv41jj.cloudfront.net/windows/luna-studio/1.0/luna-studio.tar.gz。
	打开“C:\Windows\System32\drivers\etc\hosts”（Win7），添加“127.0.0.1 d1uis3r8vv41jj.cloudfront.net”。

	别急，是“https”协议，还需要给本地Web服务器配置HTTPS、破（difficult）解（as）证（touch）书（sky），此路不通唉！
	所以特地维护了一个通过HTTP下载安装LunaStudio的LunaInstaller分支。

- [LunaInstallerOffline][2]

无论上述哪种方式安装结束后：

- 位置：C:\Users\bob\.luna
- 教辅：C:\Users\bob\AppData\Local\Temp\luna\tutorials

---
[0]:https://share.weiyun.com/bf78f65211ea424b739a4a96d3c1f66b
[1]:https://share.weiyun.com/67c88f4b8f6c950d773b38d39d9a9f91
[2]:http://luna-lang.cn/downloads.html