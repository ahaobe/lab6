# 实验目的
- Web服务调用
# 环境设置、工具
- java jdk （1.6或者以上）
- IDEA 或者 eclipse 等开发环境
# 实验任务
- 理解web Service和SOA架构。基于实验二的内容，构建web 服务。
# 实验要求
- 基于RESTful样式，对校友目录进行的插入、检索、修改、删除、统计等功能
- 后端数据库使用Mybatis或者Hibernate进行操作。
# 具体过程
### 1. 创建数据库表
![数据库表](https://i.loli.net/2019/06/19/5d09cb8b7d71e10041.png)
### 2. idea创建springboot项目
![项目结构图](https://i.loli.net/2019/06/19/5d09cc59ed2db95177.png)
### 3. 创建实体类
![Alumni实体类](https://i.loli.net/2019/06/19/5d09d7c29b21e35413.png)
### 4. 创建mapper层
![AlumniMapper接口](https://i.loli.net/2019/06/19/5d09cd9d2e03b96974.png)
### 5. 创建mapper.xml
![AlumniMapper.xml](https://i.loli.net/2019/06/19/5d09ce173a47a31528.png)
### 6. 创建dao层
![AlumniDao](https://i.loli.net/2019/06/19/5d09cf699114789807.png)
### 7. 创建service层
![AlumniService](https://i.loli.net/2019/06/19/5d09cfe6849a315865.png)
### 7. 创建controller层
![AlumniController](https://i.loli.net/2019/06/19/5d09d04c420fb88403.png)
# 结果
### 1. 显示全部校友
![select](https://i.loli.net/2019/06/19/5d09d52ca9b4b46440.png)
![selectAll](https://i.loli.net/2019/06/19/5d09cae3ea22373559.png)
### 2. 删除校友
![delete](https://i.loli.net/2019/06/19/5d09d0cde322060822.png)
![deleteresult](https://i.loli.net/2019/06/19/5d09d129d312330309.png)
### 3. 插入校友
![insert](https://i.loli.net/2019/06/19/5d09d18b9787356792.png)
![insertresult](https://i.loli.net/2019/06/19/5d09d24e8fcff14389.png)
### 4. 修改校友信息
![update](https://i.loli.net/2019/06/19/5d09d33b4a07228268.png)
![updateresult](https://i.loli.net/2019/06/19/5d09d33b4fdf517652.png)
### 5. 检索校友
![selectresult](https://i.loli.net/2019/06/19/5d09d3d96130b43580.png)
### 6. 统计校友
![countresult](https://i.loli.net/2019/06/19/5d09d43f63b0439664.png)
