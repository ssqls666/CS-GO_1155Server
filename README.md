WorldHvH.Asia免费公开1155服务器整合包

## 配置需求
最低需求:2v核心4GB内存 40Gb可用空间 20Mbps网络带宽 Ipv4公网ip一个 UDP端口正常开放
推荐需求:8v核心16GB内存 60Gb可用空间 100Mbps网络带宽 Ipv4公网ip一个 UDP端口正常开放

## 提示
此教程适用于搭载Windows Server的服务器
如有技术支援需求，请添加我的QQ:3148912176 或发送Mail给我的邮箱:ssqls@foxmail.com

## 开始搭建
首先，我们先下载并解压开服包
下载开服包方式：
123盘：https://www.123684.com/s/UzIVVv-62pY
我的个人网盘：http://download.imqfy.qpon/kaifu.zip

在数据盘创建一个文件夹(名字随意，但是不能使用中文)

<img width="1920" height="1080" alt="yp" src="https://github.com/user-attachments/assets/33a26e47-0f2b-4b71-977d-2254b7bee550" />

然后我们解压开服包里面的 steamcmd 并剪切到我们刚创建好的文件夹里面

<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/33d41397-e1d4-4342-bd5d-d772cd8acfb5" />

然后我们双击运行steamcmd

<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/c1b0da4a-d4d9-4b2a-8f01-83ff65dd18f4" />

直到出现这样我们再进行下一步

<img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/7a5feab2-f06e-4454-a271-cd4957c7a1e6" />

我们输入 "login anonymous" 进行匿名登录

<img width="1920" height="1080" alt="4" src="https://github.com/user-attachments/assets/85dd6ea4-8d2d-4273-ae61-b32b3d8b5257" />

然后我们再输入 "app_update 740 validate" 下载我们的CS:GO服务端

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/40378fbe-9d3d-4a81-aa7f-ed4827fd1227" />

当显示这样的时候，说明我们的服务端已经下载完毕

<img width="1920" height="1080" alt="5" src="https://github.com/user-attachments/assets/d97ce811-e508-4f7a-857c-64b183d40a3e" />

这时候我们再去把(插件包在开服包里面有)插件包里面的 "addone"和"cfg"文件夹 解压并放到 \steamapps\common\Counter-Strike Global Offensive Beta - Dedicated Server\csgo 里面

<img width="1920" height="1080" alt="6" src="https://github.com/user-attachments/assets/9e64866f-f0be-4229-a650-09838400939f" />

我们再把开服包里面的 "server.cfg" 放到 \steamapps\common\Counter-Strike Global Offensive Beta - Dedicated Server\csgo\cfg 里面

<img width="1920" height="1080" alt="7" src="https://github.com/user-attachments/assets/22bdfa4f-4cb4-476e-9a11-833159ffb310" />

这时候我们把开服包里面的 "start.bat" 放到 \steamapps\common\Counter-Strike Global Offensive Beta - Dedicated Server\ 里面,并双击执行

<img width="1920" height="1080" alt="8" src="https://github.com/user-attachments/assets/6973f360-e97e-496b-aca7-c563d6e083af" />

当出现这个我们就可以直接用ip进服了

<img width="1920" height="1080" alt="9" src="https://github.com/user-attachments/assets/55ab5c79-f506-4029-8e43-450088302778" />
<img width="1920" height="1080" alt="114514" src="https://github.com/user-attachments/assets/a54986f6-b5bc-4447-87d9-6d81cfdd97eb" />

## 更改服务器名字/添加密码

我们可以在 \steamapps\common\Counter-Strike Global Offensive Beta - Dedicated Server\csgo\cfg\server.cfg 里面更改我们想要的
格式如图所示(更改完后记得重启服务器)
<img width="1920" height="1080" alt="143" src="https://github.com/user-attachments/assets/7325aeab-135a-4694-8855-02629ff968b1" />

## 添加服务器管理员

我们打开 \steamapps\common\Counter-Strike Global Offensive Beta - Dedicated Server\csgo\addons\sourcemod\configs\admins_simple.ini
然后如图所示(steamid不是你的用户名或你的64,解析可以去 "steamid.io" )
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/080ddfaa-303b-401b-aa0c-67717aad2cb3" />
添加完后重启服务器就可以了

## 下面疑难杂症/常见问题

#一直连接不进去怎么办

<img width="421" height="148" alt="10" src="https://github.com/user-attachments/assets/17e22d44-c059-4f8e-ad18-5a4cb2ef3982" />

要么是你买的服务器没有ipv4独立ip（共享ip也不行）
那只能重新买台服务器

要么是你没有开放UDP协议

我们先打开控制面板，然后按着下面的图操作就行了

<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/a46d38ac-d7b3-43f1-a171-73a53b1dcf9a" />
<img width="1920" height="1080" alt="2" src="https://github.com/user-attachments/assets/339ab344-0c2b-4f59-b465-e2d08087f761" />
<img width="1920" height="1080" alt="3" src="https://github.com/user-attachments/assets/c03aa9d6-8d72-47cc-b99e-1c8ceb889413" />
<img width="1920" height="1080" alt="4" src="https://github.com/user-attachments/assets/7cb67017-71e1-4522-a012-eba927f82a40" />
<img width="1920" height="1080" alt="5" src="https://github.com/user-attachments/assets/63af5d5a-0038-4434-8858-6c7a7ad49d28" />
<img width="1920" height="1080" alt="6" src="https://github.com/user-attachments/assets/39bebcdc-b9a0-4964-8216-c933a685965c" />
<img width="1920" height="1080" alt="7" src="https://github.com/user-attachments/assets/3be05bfd-5e3a-445f-a8a4-a11ae6306ad3" />
<img width="1920" height="1080" alt="8" src="https://github.com/user-attachments/assets/c436aec7-551f-4c57-925a-b29cb74b7b4e" />
<img width="1920" height="1080" alt="10" src="https://github.com/user-attachments/assets/fcfe0d94-6566-4a06-a166-4de8c575429a" />
<img width="1920" height="1080" alt="11" src="https://github.com/user-attachments/assets/00983e05-4704-424f-9010-c52f43cab7e4" />

## 结尾

如果你觉得本期教程超级有用，那不妨施舍一点吧QwQ (bushi 
<img width="1037" height="1037" alt="1" src="https://github.com/user-attachments/assets/5af16773-1426-4e8a-b642-81f0d12c272d" />
