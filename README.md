# thinkkoa_awesome

Awesome projects for ThinkKoa.

### Plugins

名称  | used in koatty | 描述
------------- | ------------- | ------------- 
[think_apollo](https://github.com/thinkkoa/think_apollo)  | ✔️ |  Apollo Plugin . Apollo配置中心插件。
[koatty_etcd](https://github.com/thinkkoa/koatty_etcd)  | ✔️ |  Etcd Plugin . Etcd配置中心插件。

### microservice

名称  | used in koatty | 备注 | 描述
------------- | ------------- | ------------- | ------------- 
[koatty-cloud-consul](https://github.com/thinkkoa/koatty-cloud-consul) | ✔️ | 开发中 |  基于Consul的微服务管理套件，包括服务注册、发现。
[koatty-cloud-nacos](https://github.com/thinkkoa/koatty-cloud-nacos) | ✔️ | 开发中 |  基于Nacos的微服务管理套件，包括服务注册、发现，配置中心等。
[koatty-SpringCloud](https://github.com/thinkkoa/koatty-SpringCloud) | ✔️ | 开发中 |  基于SpringCloud的微服务管理套件，包括服务注册、发现。


### Middlewares

名称  | used in thinkkoa | used in koatty | 描述
------------- | ------------- | ------------- | -------------
[think_csrf](https://github.com/thinkkoa/think_csrf)  |✔️ | ✔️ |  CSRF for ThinkKoa.ThinkKoa CSRF跨站攻击安全处理中间件。
[think_i18n](https://github.com/thinkkoa/think_i18n)  |✔️ | ✔️ | Internationalization and localization for ThinkKoa.ThinkKoa国际化中间件，配合多语言文件配置，可以非常方便的实现多语言。还支持路由中指定语言。
[think_payload](https://github.com/thinkkoa/think_payload)  |✔️（embedding2.x） | ✔️（embedding3.x） | Payload parser for ThinkKoa.ThinkKoa querystring以及body解析中间件。能够解析querystring、form、file、json等多种常用数据。
[think_router](https://github.com/thinkkoa/think_router)  |✔️（embedding）| ✖ | Router for ThinkKoa.ThinkKoa路由中间件。除默认解析规则以外，还支持灵活的路由自定义规则。
[think_session](https://github.com/thinkkoa/think_session) |✔️ | ✔️ | Session for ThinkKoa.ThinkKoa Session中间件。支持file、memcache、redis等类型的session存储。
[think_static](https://github.com/thinkkoa/think_static)  |✔️（embedding） | ✔️ |  Static resource service for ThinkKoa.ThinkKoa静态文件服务中间件。生产环境建议使用nginx进行处理。
 [think_trace](https://github.com/thinkkoa/think_trace)   |✔️（embedding2.x） | ✔️（embedding3.x） |   Trace for ThinkKoa.ThinkKoa错误处理及拦截中间件。
[think_upload](https://github.com/thinkkoa/think_upload)  |✔️ | ✔️ |  Upload files for ThinkKoa.ThinkKoa文件上传功能中间件。支持本地存储、FTP、阿里云OSS等方式。
[think_view](https://github.com/thinkkoa/think_view)  |✔️ | ✔️ |  View engine for ThinkKoa.ThinkKoa视图中间件。支持ejs、jade等模板解析引擎。
[think_jwt](https://github.com/thinkkoa/think_jwt)  |✔️ | ✔️ |  JWT token for ThinkKoa. JWT token中间件，生成或检查JWT token，代替session机制，方便做单点登录。
[think_cache](https://github.com/thinkkoa/think_cache)  |✔️ | ✔️ |  缓存中间件，缓存链接初始化封装，方便应用中使用


### Librarys

名称  | 描述
------------- | -------------
[think_lib](https://github.com/thinkkoa/think_lib)  | ThinkKoa functions library.ThinkKoa常用工具函数库。
[think_queue](https://github.com/thinkkoa/think_queue)  | 基于redis的异步队列。支持错误重试，支持事件监听等高级功能
[think_loader](https://github.com/thinkkoa/think_loader)  | 目录多文件加载器
[think_logger](https://github.com/thinkkoa/think_logger)  | 控制台日志输出封装。支持info、warn、success、error等多种类型，支持颜色样式，支持日志存储
[koatty_validtion](https://github.com/thinkkoa/think_validtion)  | Validtion Util for Koatty and ThinkORM. Based on class-validator, extended parameter type checking and restricted attribute functions.
[koatty_container](https://github.com/thinkkoa/think_container) | IOC容器，支持依赖管理和自动注入
[think_thrift](https://github.com/thinkkoa/think_thrift) | thrift RPC调用封装
[think_webservice](https://github.com/thinkkoa/think_webservice) | WebService调用封装
[think_crypto](https://github.com/thinkkoa/think_crypto) | AES、DES、3DES、RSA 加密库
[think_robin](https://github.com/thinkkoa/think_robin) | 带权重的轮询策略算法
[think_request](https://github.com/thinkkoa/think_request) |  Simplified HTTP request client.


### Tools

名称  | 描述
------------- | -------------
[koatty_cli](https://github.com/thinkkoa/koatty_cli)  | Koatty command line tool.Koatty命令行工具，可以非常快速的搭建项目。
[thinkkoa_cli](https://github.com/thinkkoa/thinkkoa_cli)  | ThinkKoa command line tool.ThinkKoa命令行工具，可以非常快速的搭建项目。

### Database and cache

名称  | 描述
------------- | -------------
[thinkorm](https://github.com/thinkkoa/thinkorm)  | A flexible, lightweight and powerful Object-Relational Mapper for Node.js. ThinkORM是一个可扩展轻量级的功能丰富的对象-关系映射的数据模型封装框架，使用Node.js实现。如同SQL语言发明一样，ThinkORM试图用一种抽象的统一操作语言，使用户专注于数据操作逻辑而非具体的数据存储类型，达到快速开发和移植的目的。
[liteQ](https://github.com/thinkkoa/liteQ)  | QueryBuilder for JavaScript. Supports MySQL, PostgreSQL, MariaDB, SQLite, MS SQL Server, Oracle, and more. Works in NodeJS.轻量级、开箱即用的SQL查询构造器，支持MySQL, PostgreSQL, MariaDB, Sqlite3和Oracle。
[think_store](https://github.com/thinkkoa/think_store)  | Cache's Storage for ThinkKoa.ThinkKoa存储驱动。包括file、memcache、redis等方式。

### Example

名称  | 描述
------------- | -------------
[koatty_demo](https://github.com/thinkkoa/koatty_demo) | Koatty示例
[thinkkoa_site](https://github.com/thinkkoa/thinkkoa_site) | ThinkKoa官方网站源码

