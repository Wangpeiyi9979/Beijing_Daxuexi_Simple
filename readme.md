# 北京青年大学习
基于Github Action运行,简洁版本

在运行时获取最新一集,如未学习进行学习,已学习则结束

建议配置运行频率一周2次(默认为3天一次),没有成功会出错,默认配置下Github会向邮箱推送,所以没有推送功能

(组织不是海淀区团委可能需要修改org_id)

感谢[ouyen/qndxx-beijing](https://github.com/ouyen/qndxx-beijing)的启发,因为按自己风格改了很多东西,所以没有放在Fork中

# 配置 Secret
1. Fork
2. 填写以下SECRET （名称均为大写）: 

​		(账号密码为登录青春北京的信息,可以在[这里](https://m.bjyouth.net/site/login)测试登录信息) 

​		USERNAME: 账号  

​		PASSWORD: 密码  

​		[如何添加SECRET](https://docs.github.com/cn/actions/security-guides/encrypted-secrets#creating-encrypted-secrets-for-a-repository)

3. 在Actions界面启用定时任务(并可以手动运行一次试验)，可以在Run python中看到打印的结果信息
