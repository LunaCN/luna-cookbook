一切都是从碰到困难开始的……

萌生写一本有关Luna的Cookbook的想法时，实话说，感觉Luna真是前途未卜。

**涉及到密码的要么是luna要么是luna-lang.cn，不要慌。**

# 可恶的墙

## 安装

### 在线安装
- [LunaInstaller][0]

### 离线安装
- [LunaStudioV1.0beta][1]

网络好、速度快的朋友可以跳过，本小节针对墙内群众。

	用网络监控工具查看LunaInstaller进程，会发现在线安装LunaStudio的下载路径：https://d1uis3r8vv41jj.cloudfront.net/windows/luna-studio/1.0/luna-studio.tar.gz。
	打开“C:\Windows\System32\drivers\etc\hosts”（Win7），添加“127.0.0.1 d1uis3r8vv41jj.cloudfront.net”。
	注意到是“https”协议，还需要给本地Web服务器配置SSL。
	这里自然以IIS7为例。

---
[0]:
[1]: