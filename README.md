## 系统介绍

web框架：Django

登录&注册：Bootstrap3/4 (国外前端框架)

系统布局&效果：layui(国产前端框架"类UI")

主要工具：jQuery 3.0+、阿里云短信服务、Celery、Redis、MySql、xadmin2.0



## 功能介绍

- 用户登录、注册、各种验证基本完善(由users应用包完善)
- 系统包(system)
  - 用户管理、学生管理、编辑信息、模糊查询、添加用户、不同用户展现页面不同
  - 超管：控制用户；最高权限；全部页面。
  - 教师：发布任务；检查任务；审批；打分；可以查看学生详细信息；修改学生姓名。
  - 学生：敏感学生信息学生无法查看；提交任务。



## 目录简介

apps：应用包

celery_tasks：异步任务

extra_apps：xadmin2.0管理

Job_Files：数据库文件

static：静态文件路径

static_log：综合静态文件路径

templates：html前端模板

Work：全局项目配置文件夹

requirements.md：项目依赖包

> 先导入项目依赖包，如果有偏差自行补配下载！
>
