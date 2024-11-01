﻿=== Plugin Name ===
Contributors: smyx
Donate link: https://wptao.com/wptao-sms.html
Tags: login,register,sms
Requires at least: 3.5
Tested up to: 5.2.2
Stable tag: 1.0.3

支持手机号注册/登录，重要事件短信通知等。

== Description ==

Support mobile phone number registration / login, SMS notification.

支持手机号注册/登录，重要事件短信通知等。[进入官网](https://wptao.com/wptao-sms.html)

1. 目前支持阿里云和腾讯云短信服务。

2. 手机注册/登录/绑定只需要开启功能，在服务商申请短信模版即可使用，其中后台【手机用户】页面可以查看所有注册的手机号。

3. 短信通知使用灵活的自定义功能，支持添加多个（不上限）短信模版，可以兼容任意场景的短信通知，允许多种不同场景同时使用，只需把插件提示的一句函数加到您需要处理的代码后面即可。

4. 兼容 WooCommerce 和 Easy Digital Downloads 插件，支持订单已完成或者已退款时短信通知买家，直接开启功能即可。[查看](https://img.wptao.com/large/62579065gy1fpwh4gxajwj20u90lomyu.jpg)

5. 手机号注册兼容 BuddyPress、Ultimate Member 等注册页面，后续会根据需求兼容更多的插件。

6. WPMU可以全局配置短信服务。

7. 暂时没加图形验证码，我们采用了签名算法来防御恶意操作，后期会根据实际反馈完善更加安全的验证机制。

8. 验证码和短信通知可以设置不同的服务商（阿里云、腾讯云）。

9. 点击[这里体验一下](https://wptao.com/wptao-sms.html) （老用户建议用账号密码登录后在个人资料页面绑定手机号，4月6日0点前绑定手机号的用户将送一张满199元减20元的优惠券！）

== Installation ==

1. Upload the `wptao-sms` folder to the `/wp-content/plugins/` directory.
2. Activate the plugin through the 'Plugins' menu in WordPress.
3. Configure the settings using "SMS" under Settings panel.

下载 WordPress短信服务 插件，上传 wptao-sms 目录及其文件到 "/wp-content/plugins/" 插件目录，在后台管理中激活插件，到设置页面开启功能并设置等.

== Screenshots ==

== Changelog ==

= 1.3 =

2019/8/20

短信服务商新增【腾讯云】，目前支持阿里云、腾讯云。
为兼容【腾讯云】短信模板，WooCommerce 和 Easy Digital Downloads的订单参数有变动，请及时调整修改，需要去服务商修改或者新建。

= 1.2.6 =

2018/9/27

继续优化细节

= 1.2.4 =

2018/5/13

优化代码
后台设置新增：引导链接及关闭手机号验证码登录

= 1.2.3 =

2018/4/12

新增：用户不能解绑手机号，只能修改为新手机号

= 1.2.2 =

2018/4/9

支持手机号+密码登录

= 1.2 =

2018/4/8

手机号注册兼容 BuddyPress、Ultimate Member 等注册页面，后续会根据需求兼容更多的插件。

= 1.1 =

2018/4/6

后台增加【手机用户】页面，方便您查看用户绑定手机号的具体情况。
完善WPMU，新增全局配置短信服务。

= 1.0 =

2018/3/31

初始版本
