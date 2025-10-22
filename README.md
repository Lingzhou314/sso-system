# 单点登录系统 (SSO System)

一个简单完整的单点登录系统，基于Spring Boot + MyBatis Plus构建。

## 功能特性

- ✅ 统一认证中心
- ✅ 多应用单点登录
- ✅ 令牌管理
- ✅ 安全退出
- ✅ 会话管理
- ✅ 客户端管理

## 快速开始

### 环境要求
- JDK 1.8+
- MySQL 5.7+
- Maven 3.6+

### 数据库初始化
1. 创建数据库 `sso_db`
2. 执行 `src/main/resources/sql/sso_schema.sql`

### 启动应用
```bash
mvn spring-boot:run
