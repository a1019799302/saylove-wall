
## 线上链接
https://love.zhanghuayi.tech/

## 主要特性
- 发起表白
- 查看表白
- 搜索某人的表白
- 点赞
- 分享
- 评论
- 猜名字
- 性别区分
- 邮件通知被表白者

## 目的
脱单神器助你早日脱单。

## 快速使用

1. 数据库链接配置:
      修改connect.php中的
      <code>
      
	// $host = '127.0.0.1'; // 数据库地址
      
	// $user = 'root';  // 数据库用户名字
	
	// $pass = '';   // 数据库链接密码
	
	// $db_name = ''; // 链接的数据库名字
	
	</code>
			
      并把斜杠注释去掉，其他地方链接无需修改。
      

2. 邮件服务配置： email.php ,修改成QQ邮箱和独立密码。(需要QQ邮箱开启相关邮件服务和设置一个独立密码，使用独立密码进行登录)。此邮件服务效果并不乐观，因为QQ限制最大发邮件数量，短时间内大量邮件发送出去会被退回。建议使用第三方邮件平台，付费服务。

3. 导入数据库文件。

4. 分享链接生成：修改display.js文件第155行，此行控制生成的分享链接。

这个网站会有许许多多的BUG，欢迎大家一起来完善。

## 更新历史

## 支持
基于jQuery Mobile开发。

## 界面

![](https://pingxonline.com/wp-content/uploads/2017/08/1.png)

![](https://pingxonline.com/wp-content/uploads/2017/08/2.png)

![](https://pingxonline.com/wp-content/uploads/2017/08/3.png)
