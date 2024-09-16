本教程详细教学了如何备份降级Phigros以及获取旧版商店头像方法，涉及到的一切文件均会在文末提供相关链接

在查看教程前，请先确保：
1.你有一台iPhone/iPad(本教程使用iPad mini4-iPadOS15.7.1)
2.上述设备已越狱或安装巨魔或你掌握自签技术(即拥有证书及签名工具)
3.上述设备上安装了Phigros(制作教程时最新版为3.9.1)

##0.5备份数据(该教程失败率较低，对自己操作自信的可忽略）

* 方法一：Phi自带的TapTap云存档备份
* 方法二：越狱或巨魔使用Apps manager备份
* 方法三：使用爱思助手连接设备备份
![378C3DA3-AAA2-4F06-BB8A-302369608E83](https://github.com/user-attachments/assets/f7a4302e-4ff8-4930-889a-cb6cd5b24948)
![5FB92118-B0F2-4C93-8826-1A519BA674D2](https://github.com/user-attachments/assets/a90fceff-cc81-448d-b014-2f54136c0572)

##1.0降级Phigros(将Phigros降级到1.4.3版本)

我会在文末提供Phigros1.4.3.ipa及其他文件，至于为什么非得是1.4.3呢，会在1.5步中解释

* 方法一（需要设备上已经有自签软件及证书或电脑来使用自签软件）

首先我们需要卸载新版Phigros，防止安装旧版Phigros时出现冲突
打开 设置 点击通用/iPad(iPhone)存储空间
![FAA12E2E-548F-4812-8ED3-AA5154694DD8](https://github.com/user-attachments/assets/ee67938c-30ab-404e-b40a-7578ca4ce037)
然后等待应用列表加载(可能会花费较长时间，请耐心等待)，找到Phigros，点击它，然后点击“卸载App”，注意⚠️！是“卸载App”不是“删除App”！
![084D3EA9-C893-4252-AA7B-98F098E9D3F9](https://github.com/user-attachments/assets/ee160e93-b03e-4996-9ae6-4a88c3e9ff2f)
![94447B79-4F8A-4DA7-83D7-3BFAB2E527B1](https://github.com/user-attachments/assets/b287d8b6-b32b-49ca-9052-963adb1ec6bb)
卸载完毕之后打开你所使用的签名软件(建议用爱思助手(pc)，轻松签(iOS))
爱思助手安装ipa可自行查询，较为简单
以轻松签为例，导入Phigros1.4.3.ipa，签名进行安装（证书问题自行解决）请确保ipa签名安装时的应用标识符(Bundle Identifier)为games.Pigeon.Phigros！
![45A28CA7-E3BE-424B-B4DB-E15448E36AF7](https://github.com/user-attachments/assets/ebbbaba8-33f1-42c9-a930-561675b04c48)
* 方法二（巨魔用户可用）

A方案.
使用Trollstore覆盖安装Phigros1.4.3(前提即为标识符相同)
![9A1A6C61-F0E4-434D-A6C4-4B1FB9BAD49D](https://github.com/user-attachments/assets/bbf56f52-f748-4e50-b934-07a9cb55fe89)
选择Force Installation(覆盖安装)
![B4691A59-A879-46B4-957E-994F843885E7](https://github.com/user-attachments/assets/08538140-3449-46c9-8c28-d2dd1290cb36)
B方案.
使用Trollstore安装netskao的DowngradeApp(不推荐用Appstore++，疑似已失效)

以DowngradeApp为例，进入DowngradeApp后点击 开发者 
将其降级方式改为bilin.eu.org(或者默认的手动输入不改也行）
![963289E6-A023-459A-99E9-2A7DCD9FDDF4](https://github.com/user-attachments/assets/13052c6d-c831-4ecf-930c-971560adb08b)
回到应用列表找到Phigros，点击后选择1.4.3版本降级（有时会显示两个1.4.3，选择下面那个即可）（若上一步默认的手动输入，输入836006848即可）
![1DFA97CC-F913-4010-82AB-72C832BF4717](https://github.com/user-attachments/assets/c518c1a1-8428-4759-a205-e9c0e9b6f5b3)
![47B6B8A7-D635-4941-AD30-E5F49D911C64](https://github.com/user-attachments/assets/f16caa33-ab81-49b3-b8fe-6eb417304448)
* 方法三（越狱可用）
使用netskao的AppData插件进行App降级
![810D1ECE-4914-4AAB-AFE0-3F3E12F4257A](https://github.com/user-attachments/assets/8ecfac06-a83f-45e1-b42a-a40bb86e3770)

##1.5刷取data，购买头像

降级有商店的版本之后，我们需要有足够的data来购买头像(约64MB)
在1.4.3版本，增加了通关新手教学(880000分及以上)会给予32MBdata的行为，且该版本有一个bug，即你打了多少遍新手教程，就能获得多少次32MB的data
![777DDE3C-3D85-46EF-A5F9-434C6C4FAE4D](https://github.com/user-attachments/assets/386f0434-a684-4ad1-8577-ebe7fa61bdb1)
初次进入1.4.3版本时，游戏会直接判定你为新用户，让你进行新手教程，不要惊慌，你的高版本数据并没有丢失或受到影响，因为Phigros在高版本某次更新中加密了存档结构，所以导致旧版本无法识别。
![935BD92A-5431-48A7-B49A-45EB668A2CF3](https://github.com/user-attachments/assets/ca5c2e12-a8d3-43e7-91e9-40f107726004)
这时我们只需要正常地打一遍新手教程，然后再打一遍新手教程，来获得我们购买商店头像的资金（每次新手教程需要超过880000分）
![1E6542CB-FD28-4F6E-A85B-A64A42C44205](https://github.com/user-attachments/assets/0fd5ae3d-a3b3-4847-ab7e-76836cacbc1a)
获取完足够的data之后，来到游戏主界面，点击左上角线索栏，然后在线索界面点击右上角的商店栏，即可进入商店，购买头像
![CA7565B2-B3D5-4E9D-BB35-46DB0FBB7E07](https://github.com/user-attachments/assets/f93d5ee7-6a27-45ae-87a4-ee78651aee80)
(Phigros从1.4.3到最后一个带有商店的版本1.6.12之间，没有在商店增加任何新头像，所以无需担心没有购买到全部的商店头像

##2.0升回高版本，查看成果

当你购买完全部的商店头像，即可将Phigros升级回高版本

假如你在之前降级时候采取的是巨魔覆盖安装或DowngradeApp或者越狱使用AppData降级
那么你可以直接打开AppStore，搜索Phigros，点击更新
![4A893176-6B5C-48F3-B8FF-B6C73E75AE11](https://github.com/user-attachments/assets/d36c6e3b-a725-485d-a9ee-176000574a72)
假如你之前降级时使用的是自签类的方法
你或许还需要使用自签之前的卸载Phigros方法(注意不是删除)，来解除安装冲突，然后进入AppStore，搜索Phigros，点击下载(或☁️图标)
![405CFE66-8970-4A64-BAA4-1E7D536C7658](https://github.com/user-attachments/assets/4d1b1897-957a-4e99-b8b3-45b11720a7d3)

等待更新完成，进入游戏，就能前往个人页面查看自己获得的商店头像啦，而且存档没有出现任何问题！
![511906A4-CADA-482C-A474-D715E8297877](https://github.com/user-attachments/assets/6ccdead6-f402-4aeb-b3b8-1f850576257d)

##相关文件及链接
Phigros1.4.3.ipa(标识符需自行修改):https://pan.baidu.com/s/1Sn-0Ieu-jnryfaX4ND_GPg 提取码：1234

DowngradeApp(netskao).tipa:https://pan.baidu.com/s/14wTi_0vjbTg_1qe9EM-ZEA 提取码：1234

AppData(netskao).deb:https://pan.baidu.com/s/1-iJ-PMUMHkro3ozGNxQUww 提取码：1234

netskao频道:https://t.me/IPAPatch

netskao越狱插件源:https://jailrepo.initnil.com/

AppsManager越狱插件源:http://apt.thebigboss.org/repofiles/cydia/dists/stable

轻松签:https://esign.yyyue.xyz/index.html

爱思助手:[www.i4.cn](https://m.i4.cn/)
