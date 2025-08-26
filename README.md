<p><h1 align="center">汽车维修管理系统</h1></p>

- <b>完整代码获取地址：从戎源码网 ([https://armycodes.com/](https://armycodes.com/))</b>
- <b>技术探讨、资料分享，请加QQ群：692619798</b> 
- <b>作者微信：19941326836  QQ：952045282</b> 
- <b>承接计算机毕业设计、Java毕业设计、Python毕业设计、深度学习、机器学习</b>
- <b>选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 一条龙服务</b>
- <b>所有选题地址 ([https://github.com/YuLin-Coder/AllProjectCatalog](https://github.com/YuLin-Coder/AllProjectCatalog)) </b>


## 一、系统介绍
本项目前后端分离(还有ssm版本)，分为用户、维修员、员工、管理员四种角色
### 1、用户：
- 注册、登录、维修预约、预约记录管理、预约台账、个人信息、密码修改

### 2、维修员：
- 维修记录管理、开维修单、配件领用、汽车修理台账、配件领用管理、配件库存查询、配件申请管理

### 3、员工：
- 车辆管理、维修预约管理、汽车维修单管理、配件领用管理、维修台账管理、配件库存管理、采购进货管理、配件申请管理、统计报表

### 4、管理员：
- 包括员工和维修员所有功能、客户管理、维修员管理、员工管理、维修项目管理、项目类型管理

## 二、所用技术

后端技术栈：

- Springboot
- mybatisPlus
- Mysql
- Maven

前端技术栈：

- Vue
- Vue-router
- axios
- elementUi

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上, Maven3.6, node14

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 论文截图
![contents](./picture/picture0.png)
### 1、用户：
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
### 2、维修员：
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
### 3、员工：
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
### 4、管理员：
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)

## 五、浏览地址

后端登录：http://localhost:8081

客户账号密码：客户1/123456

员工账号密码：员工1/123456

维修员账号密码：维修员1/123456

管理员账户密码：admin/admin

## 六、部署教程
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件

2. 使用IDEA/Eclipse导入carRepair项目，若为maven项目请选择maven，等待依赖下载完成

3. 修改application.yml里面的数据库配置,src/main/java/com/SpringbootSchemaApplication.java启动后端项目

4. vscode或idea打开src/main/resources/admin目录

5. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run serve启动,执行成功后会显示访问地址
