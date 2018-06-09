# lli-drools

### 导语
#spring-boot-drools7
> spring-boot整合drools7，数据库实现drools规则文件的增删改查及加载  
> Drools默认加载 *.drl 文件,目前能想到的有两种方案加载规则信息  
> * 1.数据库实现规则的增删改查,然后拼装规则信息,交给规则引擎编译  
     优点:相对灵活,但是后期运维方便  
     缺点:组装稍显麻烦,尤其逻辑复杂度高的规则  
> * 2.指定规则文件位置加载,例如: FTP 或 MongoDB  
     优点:规则编写容易  
     缺点:运维成本高

### 声明
> 以上内容仅是个人见解,还在学习中......

### 使用
> 以下为项目使用介绍  
> 下载当前项目之前,请先下载其引用项目 [lli-base](https://github.com/haohao1121/lli-base) 和 [lli-utils](https://github.com/haohao1121/lli-utils)  
> lli_drools.sql 脚本可以直接导入MySql数据库,里面包含测试数据  

### 遗憾
> 目前没有前端代码的实现,前端框架VUE,本人正在学习中,后期会实现  
如果有前端高手,可以帮忙搭建一个前后端分离的框架,可以[邮件](812080908@qq.com)通知我,不胜感激  
有任何建议或者好的方案大家可以一起共勉,最后,JAVA万岁 ^_^