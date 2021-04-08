
# 获取cookie
安装多看点刷金币，使用HttpCanary等抓包工具，打开软件后进入我的页面
搜索user/index地址，页面中抓取cookie,参数类似

```
let dkdurl ='http://dkd-api.dysdk.com/user/index'
let dkdhd = '{"headerInfo":"eyJvcXXXXXXXwOWMyOTdkMjcXXXXXXXbiI6IjEwODAqcXXXXXXX=","Content-Type":"application/x-www-form-urlencoded"}'
let dkdbody = 'token=cc14402e1XXXXXXX5c2845'
```

# 操作步骤
## Step 1 Fork仓库
打开[代码链接](https://github.com/qianx443/dkd)并Fork我的仓库

##  Step 2 设置Cookie
fork完之后,如图点击<font color="red">Settings</font>
进去之后依次点击<font color="red">Secrets----new secret</font>
点击之后
 - ame输入dkdurl, value输入你的dkdurl
 - 完成后点击add secret 
 - Name输入dkdhd, value输入你的dkdhd，注意参考上文中示例，修改成json格式，仅需替换headerInfo内容
 - Name输入dkdbody, value输入你的dkdbody
 - 同理再添加一个sckey,  value输入你的server酱Key [获取地址](https://qmsg.zendee.cn)以及sckey(server酱)


## Step 3 启用Actions
点击Action，再点击**I understand my workflows, go ahead and enable them**  
![avatar](https://cdn.jsdelivr.net/gh/Wenmoux/wenpic/687474703a2f2f74752e79616f68756f2e6d652f696d67732f323032302f30362f333463613136306339373262393932372e706e67.png)
## Step 4 运行结果 
点击Actions-dkd-auto-coin查看
![avatar](https://attach.52pojie.cn/forum/202102/05/092214uaii8arlvaqmf04r.png)
![avatar](https://attach.52pojie.cn/forum/202102/05/090000hqub17o591v979nn.png)

## 其它说明
 - 设置好之后要点击Actions启用下
 - 可以自己改定时时间
 - 还没想到
 - 不介意的话请输入作者邀请码13209301得500金币
 - 如果没有自动触发workflow，请先确认是否已经enable workflow，然后任意修改下readme.md文件并commit changes
