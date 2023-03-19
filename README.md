# get-vpn
网络加速器、海外节点，科学上网（文件夹里有pdf版可以下载）
## 简介：
### 本文以window和安卓为例，使用holytech梯子（虚拟服务器）和Clash（用以连接）来搭建科学上网的条件，让您更轻松地访问国外网站和服务。
## 注意：
### FQ的行为在中国大陆地区不被鼓励，甚至可能违反当地的法律法规。在使用此类工具时，请遵守相关法律法规和平台规定，并且评估好风险和代价，不要从事任何违法活动。同时，请注意网络安全和个人隐私保护。
## 正文：

## 购买holytech服务
### 该网站可提供退款服务，且运行多年，相对还是比较稳定可靠的（亲测YouTube不卡顿），并且价格算很优惠了，一年100块都不到！当然了，大家也可以选择其他类型的梯子，但基本都需要花费一定的资金，贵也有贵的道理，专人专线肯定好过多人拥挤在一个节点线，也更安全和稳定，网上都可以搜到教程哈，这里就不赘述了，大家自行选择是否要购买哈，要是小伙伴门觉得用的不顺心，可以点击退款，另外选择其他VPS。（大家尽量不要使用免费的，不仅多人用网速差，很多可能携带病毒，不安全）
## 1、注册
### 注册并登录holytech官网：https://store.holytech.tech/clientarea.php
## 2、购买服务
### 登陆后，如果看不懂英文，可在右上角选择繁体中文
## 在顶部菜单栏点击Services→Order new services可以跳转到套餐页面
### 目前Holytech售卖的套餐如下图所示，共有三款v2ray套餐。
![2](https://user-images.githubusercontent.com/38072036/226147525-9f391fec-801a-4774-a17b-33779f0a836a.png)

### 第一个是试用套餐，輸入優惠碼 “v2trial”價格會調整至 $0.15，约合人民币1.03元。后两个是正式套餐。正式套餐的唯一区别是每月流量不同，可以根据个人使用量选择不同套餐。购买支持支付宝。

### 大家可以先用试用版或者一个月的试试水
### 购买完后既可以在My services查看当前生效的套餐。
![3](https://user-images.githubusercontent.com/38072036/226147537-ac12a0e1-4516-4957-86c7-30fcc9442992.png)

### 点击进去，就可以看到该服务提供的各种节点详情啦
![5](https://user-images.githubusercontent.com/38072036/226147570-27930d71-b71d-453f-ada8-410fb8ec5cce.png)
### 在此页面找到服務信息--【订阅地址URL】，至此，服务已购买完毕，暂且停留，不要关闭网页，进入下一步操作--搭建连接服务。
![6](https://user-images.githubusercontent.com/38072036/226147591-5923265e-e453-4b2c-93e1-e401a5749a17.png)


## 搭建连接服务
### Holytech提供了两种使用办法：一种是安装他们自己制作的一键上网软件（点击购买的服务产品里即可找到）。安装后，直接打开并登陆自己的购买帐号即可上网。官方教程很详细，这里也不展开叙述。选择这种的大家就不需要往下看啦
![7](https://user-images.githubusercontent.com/38072036/226147600-fc8c7eb5-93c5-429d-bf4c-cea2b86494c5.png)

### 另一种是使用开源v2ray软件自己进行配置。例如Windows系统可以选择用clash，安卓可以用v2rayNG，苹果手机可以用小火箭，直接将配置信息复制进去就可以上网了，也比较方便。

### 我这边使用第二种方法：
## 安卓手机版：
### 进入https://github.com/Kr328/ClashForAndroid/releases ，选择对应型号的安装包，我是华为mate手机，第一个就🆗，如果手机提示无法安装，大概率是型号不匹配，多试几个。
![8](https://user-images.githubusercontent.com/38072036/226147604-cb042001-a44b-4735-a429-507bde93b989.png)

### 将安装包发送到手机，可以使用微信传文件。下载后，选择用浏览器打开，如果没有合适的浏览器，可以利用手机的【文件管理】找到该文件并选择打开为【应用】，即可安装软件
![9](https://user-images.githubusercontent.com/38072036/226147623-bc385755-1af9-481e-a898-9c8c0881ac8e.jpg)

### 点击手机上的图标
![10](https://user-images.githubusercontent.com/38072036/226147627-d2786f6d-cedb-4042-a8b1-0ec7acc84703.jpg)

### 1、进入配置页面，将Holytech页面里的对应型号的配置URL复制进去，保存
![11](https://user-images.githubusercontent.com/38072036/226147656-4d7bb791-842b-4995-afa1-3dc7e69807d8.png)
![12](https://user-images.githubusercontent.com/38072036/226147657-3741e0a1-5b19-4ff7-ae76-00717b877482.png)
![13](https://user-images.githubusercontent.com/38072036/226147651-f77407cb-30f0-41cc-ad55-335385269b81.png)

### 2、最后点击右上角的保存并勾选该配置文件。
![14](https://user-images.githubusercontent.com/38072036/226147665-fd690503-a9ec-466d-b0f9-c12069944b52.png)
### 3、启动，选择代理，便可以看到该配置URL关联的所有节点，先测速，勾选适合的节点。大功告成！
![14](https://user-images.githubusercontent.com/38072036/226147672-5713f462-cb58-47bb-ba7f-c6e8698aa992.png)
![15](https://user-images.githubusercontent.com/38072036/226147677-bc4df4ca-474c-4407-b597-ea27484cabbc.png)

### 一般来讲，离中国越近，网速会越快。

## 电脑版：
### 1、进入https://github.com/Fndroid/clash_for_windows_pkg/releases 并选择对应电脑型号的安装包，如果安装不成功，大概率是型号对不上，可多下载几个试试。
![16](https://user-images.githubusercontent.com/38072036/226147686-988eaa84-7fcf-48a1-a6c0-8ae1a98f4326.png)

### 解压后，直接打开 Clash for Windows 应用程序（可以右击选择-> 发送到->桌面快捷键，方便后面直接桌面就可以点击应用程序打开。）
![17](https://user-images.githubusercontent.com/38072036/226147708-b93462fc-3c94-46bd-9c4d-cec0ecb1fc5b.png)

### 打开后如图
![18](https://user-images.githubusercontent.com/38072036/226147878-b6dce6b5-0c77-4d07-8f78-69d7fe553161.png)

### 通过订阅链接下载配置文件，在(Profiles)配置文件一栏里面，复制你购买订阅的链接 URL（回到Holytech页面进行复制URL），然后点击 download（下载）按钮下载订阅文件
![19](https://user-images.githubusercontent.com/38072036/226147880-9f883341-ff5e-428f-ae54-fe151999ca16.png)

### 切换到 proxies（代理）一栏，会看到很多节点，单击无线图标可以查看延迟等。选择你的节点，用鼠标点下即可。其他不懂的不要动。
![20](https://user-images.githubusercontent.com/38072036/226147881-6c3112a0-61fb-4a30-91e9-9672f50f0e2a.png)

### 最后，打开系统代理，大功告成！
![21](https://user-images.githubusercontent.com/38072036/226147884-4c0f7148-7048-4542-9e22-33559a369741.png)


## 注意
### 1、如果还是上不了网，可以先删除先前的配置文件，然后通过 url 重新下载就可以解决问题了。如果还不行，多试几次，也可以给HOLYTECH客服留言（建立服务单）反馈问题，实在不行就退款。
### 2、如果网速差，可以重新测速，选择其他节点。

