# OnlineOfficeServer
vue项目MyBlog配套服务端代码（持续更新）



- **使用 gorm 访问数据库**

- gin 为项目根目录

- main.go 为入口文件

- Router 为路由目录

- Middlewares 为中间件目录

- Controllers 为控制器目录

- Services 为服务层目录，这里把 DAO 逻辑也写入其中，如果分开也可以

- Models 为模型

- Databases 为数据库初始化目录

- Sessions 为 session 初始化目录

- 文件 **引用顺序** 大致如下

  main.go（ 在main中关闭数据库 ）- router（ Middlewares ）- Controllers - Services(sessions) - Models - Databases
