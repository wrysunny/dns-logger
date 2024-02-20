# DNS Logger   
## 说明  
不是 http://dnslog.cn/  等平台的功能！！！  

用来记录、排查网络中哪台机器访问了特定的网站（挖矿），方便应急响应时进行定位。  

## 方法  
配置文件不存在时先运行一下就会自动生成。   

修改配置文件中的上游dns服务器（默认为阿里、腾讯DNS）  

管理员运行它  

设置网络中dns服务器为运行此软件的机器ip  

有访问记录会保存到sqlite数据库中，内容有时间、主机ip、查询类型、查询内容等。  

## 效果  

运行截图：  
![Snipaste_2024-02-20_15-49-25](https://github.com/wrysunny/dns-logger/assets/20748454/67f15896-5dfe-4a15-95a2-452155483d02)  


数据库内容：  
![Snipaste_2024-02-20_15-49-56](https://github.com/wrysunny/dns-logger/assets/20748454/ea3f3888-d9ff-4b6d-87f1-8c59fec87e6b)  
