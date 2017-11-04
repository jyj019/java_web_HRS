# HRS(实现功能)

### 系统简介

本系统一个人力资源管理系统(HRS)，系统包括用户登录注册，部门显示修改删除，员工显示修改删除等模块。系统使用了前端技术jQuery库及其ajax实现分页功能和使用Bootstrap框架制作页面，表示层运用了MVC架构，jsp作为视图servlet作为控制器；业务逻辑层运用事务脚本模式；持久层使用了SQL直接实现CRUD操作，底层使用MySQL实现数据存取。

### 实现功能

用户：输入用户名和密码登录，输入用户名，密码和邮箱注册。

部门：根据部门编号**显示**、**修改**和**删除**部门的编号、名称和地址。 

员工：根据部门编号按**分页显示**员工信息，单击员工姓名**显示**员工信息详情，在显示页面**增加**员工，根据员工编号**修改**员工信息和**删除**员工，并在删除员工后显示页面使用**ajax**刷新

### 项目管理及系统架构

开发工具：Eclisp

数据库：MySql 5.7.1

jdbc连接：采用dbcp2连接池

Servlet容器：tomcat9.0
