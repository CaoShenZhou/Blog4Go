# Blog4Go
### 项目介绍
```
基于Go的Gin框架开发的博客系统
```

### 更新日志
```
版本：v0.0.1

2022.06.17
- 完善登录、注册、获取验证码接口
- 修复验证码重复问题

2022.06.16
- 优化项目结构
ps:断更近四个月了，一直在忙公司的项目，从里面也学到了不少东西，对Go也更加的了解了，尽量每周更新一次项目

2022.02.24
- 加入了JWT中间件和路由组(公开组不需要token，私有组则需要)

2022.02.23
- 细分功能模块，链式调用更方便

2022.02.20
- 编写发送文本邮件方法
- 编写了获取指定长度的随机字符串方法
- 编写了注册用户和验证注册邮箱接口
- 业务处理归纳到了service
- SQL处理归纳到了dao

2022.02.18
- 编写redis连接方法

2022.02.17
- 编写JWT生成和解析方法
- 细化出了VO模型(只存放需要的数据)
- 编写了MD5工具类

2022.02.14
- 编写配置文件读取工具
- 编写数据源连接方法
- 更新了通用响应方法和响应码
- 细化出了Entity模型(映射数据表)和DTO模型(校检数据)

2022.02.14
- 建立项目大体
- 编写模块路由
- 编写项目统一响应体
- 编写用户表和文章标签表
- 编写加解密和UUID工具类
```