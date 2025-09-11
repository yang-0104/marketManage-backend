# 超市管理系统后端（marketManage-backend）

本项目是一个基于 Spring Boot 的超市管理系统后端，旨在为超市运营提供高效、稳定的数据服务和业务支撑。系统涵盖用户管理、商品管理、订单处理、购物车、地址管理、餐厅管理、配送管理等核心功能。

## 技术栈
- Java 8+
- Spring Boot
- MyBatis-Plus
- JWT 用户认证
- RESTful API 设计

## 主要功能模块
- 用户注册与登录
- 商品分类与管理
- 购物车操作
- 订单提交与查询
- 地址管理
- 配送员管理
- 餐厅信息管理
- 异常处理与拦截器

## 项目结构
- `controller/` 控制器层，处理前端请求
- `service/` 业务逻辑层
- `entity/` 实体类
- `mapper/` 数据访问层
- `config/` 配置类
- `util/` 工具类
- `exceptions/` 自定义异常
- `interceptors/` 拦截器

## 启动方式
1. 配置好数据库连接信息
2. 使用 IDE 或命令行运行 `SoftwareTakeoutApplication.java`
3. 访问对应接口进行功能测试

## 适用场景
适用于中小型超市、餐饮外卖平台等需要后端数据管理和业务支撑的场景。

