# Mythology Game

一个以中国神话为主题的综合游戏应用，包含Vue.js前端和Spring Boot后端。

## 项目结构

```
mythologyDemo/
├── Myth-Destiny/          # Vue.js前端应用
│   ├── components/        # Vue组件
│   ├── pages/            # 页面组件
│   ├── static/           # 静态资源
│   └── ...
├── mythology/            # Spring Boot后端应用
│   ├── src/main/java/    # Java源代码
│   ├── src/main/resources/ # 配置文件
│   └── ...
└── logs/                 # 应用日志
```

## 技术栈

### 前端
- **Vue.js 3** - 渐进式JavaScript框架
- **Vue Router** - 路由管理
- **Pinia** - 状态管理
- **Vant** - 移动端组件库
- **Uni-app** - 跨平台开发框架

### 后端
- **Spring Boot 3.x** - Java后端框架
- **Spring Security** - 安全框架
- **MyBatis-Plus** - 数据访问层
- **MySQL 8.0** - 主数据库
- **Redis** - 缓存和会话存储

### 部署
- **Docker** - 容器化部署
- **Nginx** - 反向代理和静态资源服务

## 功能特性

- 🎮 完整的游戏系统
- 👤 用户管理和认证
- 🏛️ 神话世界构建
- 📱 响应式设计，支持移动端
- 🔐 JWT认证和权限控制
- 💾 数据持久化和缓存

## 快速开始

### 环境要求
- Node.js 16+
- Java 17+
- MySQL 8.0+
- Redis 6+

### 前端启动
```bash
cd Myth-Destiny
npm install
npm run dev
```

### 后端启动
```bash
cd mythology
mvn spring-boot:run
```

### Docker部署
```bash
docker-compose up -d
```

## API文档

后端API文档可通过访问：
```
http://localhost:8080/swagger-ui.html
```

## 项目特色

- **神话主题**: 以中国神话为背景构建游戏世界
- **跨平台**: 支持Web、移动端等多平台访问
- **模块化**: 前后端分离，易于维护和扩展
- **高性能**: 使用缓存和优化策略提升性能
- **安全可靠**: 完善的安全机制和权限控制

## 开发指南

详细的开发文档请查看 `docs/development_guide.md`

## 许可证

MIT License