# 1.1 演示

[http://oursmedia.cn](http://oursmedia.cn) 东莞市傲咪迪数据技术有限公司

## 演示平台提示
+ 请使用浏览器全屏模式, 
+ 不可使用刷新等实际设备上不存在的按钮
+ 兼容16：9, 4：3两种比例
+ 兼容firefox, chrome
+ 会员登录部分任意输入

## 演示功能
+ 货道故障
+ 缺货
+ 购物车
+ 现金支付
+ 会员购买
+ 会员充值
+ 终端管理货道测试
+ 终端管理充零钱
+ 终端管理补货
+ 终端管理补充硬币
+ 终端管理在线升级
+ 终端管理关机

## 与实际平台的差异
+ 没有实际硬件设备连接,
  + 在模拟设备返回时,用户操作可能失效. 比如充零钱时,操作终止,但此时设备仍然会收到验钞信息,因此用户操作失效
+ 没有实际后台数据
  + 在模拟提交订单,补充硬币,测试货道,补充商品等功能时,没有实际的数据更改,因此看到的数据会没有变化
+ 会员登录失败没有警告信息, 帐号锁定10分钟功能.
  + 因为会员登录没有进行服务器实际验证
  
# [开始演示](http://vendingui.demo.oursmedia.cn)