# ibm_cf_restart-actions
使用Github Actions定时重启IBM Cloud Foundry应用程序

## 使用之前，有几项准备工作
1.IBMCloud的账号
2.Cloud Foundry应用程序的区域
3.Cloud Foundry应用程序的名称

## 使用方法

### 1 Fork此仓库

### 2 设置此仓库的变量

![](http://sennqm.iwater.pw/images/2020/06/16/TIM20200616181839.png)

依次添加名为**MAIL**、**PWD**、**RGN**、**CFNAME**的变量
值分别为邮箱(账号)、密码、区域、Cloud Foundry应用程序的名称

### 3 点击star或者任意方法使Actions激活

此前，可能需要点击**Pull requests**于**Projects**中间的**Action**进去点一下允许之类的

### 变量示例
MAIL====>12345@qq.com  
PWD====>123456QWER  
RGN====>us-south  
CFNAME====>cxkjntm  

## 其他

配置完毕，将会在每天的04:15重启Cloud Foundry应用程序
