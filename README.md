
# [SUT打卡自动化——基于Python requests](https://github.com/usbcsusb/SUT-AutoReport-python)

![GitHub last commit](https://img.shields.io/github/last-commit/usbcsusb/SUT-AutoReport-python)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/usbcsusb/SUT-AutoReport-python)  

友情链接 https://github.com/BioniCosmos/auto-report

## 食用方法

本分支为非github action 版本 ，直接使用 python main.py 即可运行
Github Action版本 在另一个分支

定时运行 ：
先在服务器内安装python依赖
pip install -r requirements.txt

之后在宝塔面板中选择一个文件夹用来存放main.py 
编写 运行时间和执行脚本 
![image](https://user-images.githubusercontent.com/57305002/160044243-1a02b49a-7e13-4b0b-8157-b1ac85c19079.png)

在 main.py 中修改相关参数

    user_account = "*********"  # 学号
    user_password = "*******"  # 身份证后六位
    mqszd = "沈阳市"  # 目前所在地 填写 "沈阳市" 、 "辽宁省非沈阳市" 、"其他地区（非辽宁省）"
    sfybh = "否"  # 前一日填报到目前为止，目前所在地（第 1 题）是否存在变化？ 填写 “是” 、 “否”
    jrcltw = "36.5"  # 今日测量体温
    sjhm = "187*****"  # 请填写目前个人手机号码
    jrlxfs = "#187******"  # 请填写家人联系方式
    zddw1 = "中国,辽宁省,沈阳市"  # 目前所在地第一行
    zddw2 = "沈阳工业大学"  # 目前所在地第二行
    # 微信推送 key 在 https://sct.ftqq.com/login 中使用微信扫码获取，信息会推送到你扫码的微信号上。
    SendKey = "****************************************"
微信推送 key 在 https://sct.ftqq.com/login 中使用微信扫码获取，信息会推送到你扫码的微信号上。
<div align="center">
	<img src="images/img 0.png" width="100%">
</div>
    扫码之后点继续
    <img src="images/img 1 .png" width="100%">
    点击复制
    <img src="images/img 2 .png" width="100%">
    将复制的SendKey粘贴在 ******************位置 
     <img src="images/img 3 .png" width="100%">


## 许可证声明：
本项目采用MIT许可证
* 你可以使用，复制和修改软件
* 你可以免费使用软件或出售
* 唯一的限制是，它是必须附有MIT授权协议

# 郑重声明：
**本项目初衷为学习python基础！**

**本项目使用者在使用前应了解本项目所带来的风险！**

**本人不对此项目所造成的一切后果担责！**
