#easytrader

修改了follower：headers中增加cookies，修改user_agent,否则无法获取雪球组合调仓信息

调整了balance读取设置，否则海通系统字段不同，无法读取balance数据

需要在下单系统中设置软件默认买卖价格为空

增加了跟单系统中对交易时间的判断，非交易时间自动break

为确保跟单可以跟进，当前买卖单均调整了2%，买价挂高2%，卖价挂低2%
