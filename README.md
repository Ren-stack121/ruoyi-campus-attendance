# 🎓 ruoyi-campus-attendance

> 高校考勤管理系统（二次开发）：基于 RuoYi + SpringBoot + MyBatis + Redis + Vue + Element 的后台权限管理平台

## 📌 项目简介

本项目基于 [RuoYi-Vue](https://github.com/yangzongzhuan/RuoYi-Vue) 框架进行复刻与裁剪，结合校园管理场景新增如下功能模块：

- 学生信息管理
- 考勤记录管理
- 课程排班与签到统计

用于模拟一个高校场景下的后台系统，支持权限控制、数据缓存、模块扩展、前后端分离。

## 🔧 技术栈

- 后端：Java 8、Spring Boot、MyBatis、JWT、Redis
- 前端：Vue.js、Element UI
- 数据库：MySQL 5.7+
- 工具链：Maven、Postman、Nginx（可部署）

## ⚙️ 自定义功能（相较于原始 RuoYi）

- 新增“考勤信息管理”模块，支持学生按课程打卡
- 调整菜单权限结构，剔除不相关模块（如代码生成、定时任务等）
- 自定义表单 + 页面，适配考勤与课程管理业务
- 补充前后端接口文档，增强系统可演示性

## 💡 学习目标

- 熟悉大型 Java 后端项目结构与权限控制逻辑
- 掌握 Spring Boot 项目实战开发与常用中间件（Redis、MySQL）使用
- 学会 Fork、精简、定制开源项目作为个人求职展示项目

## 📎 项目地址

GitHub: [https://github.com/Ren-stack121/ruoyi-campus-attendance](https://github.com/Ren-stack121/ruoyi-campus-attendance)

---

本项目仅作为个人学习使用，原框架版权归 [RuoYi 作者](https://gitee.com/y_project/RuoYi-Vue) 所有。
