# Awesome Flask资源汇总（中文版） [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> Awesome Flask资源汇总
- [Awesome Flask](#awesome-flask)
  - [框架](#framework)
  - [后台管理](#admin-interface)
  - [数据分析](#analytics)
  - [认证](#authentication)
  - [授权](#authorization)
  - [数据库](#database)
  - [数据库迁移](#database-migrations)
  - [会话](#session)
  - [缓存](#cache)
  - [数据校验](#data-validation)
  - [邮箱](#email)
  - [i18n](#i18n)
  - [全文搜索](#full-text-searching)
  - [限流](#rate-limiting)
  - [任务队列](#task-queue)
  - [异常追踪](#exception-tracking)
  - [链路追踪](#tracing)
  - [APM](#apm)
  - [其他  SDK](#other-sdk)
  - [前端](#frontend)
  - [开发 (调试/测试/文档)](#development-debuggingtestingdocumentation)
  - [工具类](#utils)
- [资源](#resources)
  - [指南](#tutorials)
  - [课程](#courses)
  - [书本](#books)
  - [幻灯片](#slides)
  - [视频](#videos)
  - [基于 Flask 的项目](#built-with-flask)
  - [样板](#boilerplate)

## 框架

- [Connexion](https://github.com/zalando/connexion) - 基于 Flask 的 Python Swagger/OpenAPI 优先框架，支持自动端点验证和 OAuth2。
- [Flask-MongoRest](https://github.com/closeio/flask-mongorest) - 基于 MongoEngine 的 Restful API 框架
- [Eve](https://github.com/pyeve/eve) - 使用 Flask 和 MongoDB 构建的 REST API 框架，带有良好设计理念
- [Flask-Restless](https://github.com/jfinkels/flask-restless) - Flask 扩展，用于从 SQLAlchemy 模型快速创建简单的 RESTful API
- [Flask-RESTful](https://github.com/flask-restful/flask-restful) - 用于创建 REST API 的简易框架
- [Flask-RestPlus](https://github.com/noirbizarre/flask-restplus) - 提供语法糖、辅助工具，并可自动生成 Swagger 文档
- [Flask-Potion](https://github.com/biosustain/potion) - 基于 Flask 和 SQLAlchemy 的 RESTful API 框架
- [Zappa](https://github.com/Miserlou/Zappa) - 在 AWS Lambda 和 API Gateway 上构建和部署无服务器 Flask 应用

# 管理后台

- [Flask-Admin](https://github.com/flask-admin/flask-admin) - 简单且可扩展的 Flask 管理后台框架

## 数据分析

- [Flask-Analytics](https://github.com/citruspi/Flask-Analytics) - 为 Flask 框架生成分析脚本片段的扩展  
- [Flask-Matomo](https://github.com/Lanseuo/flask-matomo) - 使用 Matomo 跟踪对 Flask 网站的请求

## 认证

- [Flask-Security](https://github.com/mattupstate/flask-security) - 为 Flask 应用提供快速简便的安全机制  
- [Flask-Login](https://github.com/maxcountryman/flask-login) - Flask 用户会话管理  
- [Flask-User](https://github.com/lingthio/Flask-User) - 可定制的 Flask 用户账户管理  
- [Flask-HTTPAuth](https://github.com/miguelgrinberg/Flask-HTTPAuth) - 为 Flask 路由提供 Basic 和 Digest HTTP 认证的简单扩展  
- [Flask-Praetorian](https://github.com/dusktreader/flask-praetorian) - 为 Flask API 提供强大、简单、精确的安全机制（基于 JWT）

## 授权

- [Authlib](https://github.com/lepture/authlib) - 功能强大的 OAuth 1、OAuth 2、OpenID 客户端和服务器认证库  
- [Authomatic](https://github.com/authomatic/authomatic) - 提供开箱即用的 OAuth 1.0a（Twitter、Tumblr 等）和 OAuth 2.0（Facebook、GitHub、Google 等）支持  
- [Flask-Pundit](https://github.com/anurag90x/flask-pundit) - 基于 Rails 的 [Pundit](https://github.com/varvet/pundit) 扩展，为模型访问控制提供简便方式  
- [Flask-Dance](https://github.com/singingwolfboy/flask-dance) - Flask OAuth 客户端扩展，预设支持 Facebook、GitHub、Google 等

## 数据库

- [Flask-MongoEngine](https://github.com/MongoEngine/flask-mongoengine) - 支持 WTF 表单的 MongoEngine Flask 扩展  
- [Flask-SQLAlchemy](https://github.com/mitsuhiko/flask-sqlalchemy) - 为 Flask 添加 SQLAlchemy 支持

## 数据库迁移

- [Flask-Migrate](https://github.com/miguelgrinberg/Flask-Migrate) - 使用 Alembic 的 Flask SQLAlchemy 数据库迁移工具

## 会话

- [Flask-Session](https://github.com/fengsp/flask-session) - Flask 服务器端会话扩展

## 缓存

- [Flask-Caching](https://github.com/sh4nks/flask-caching) - 为 Flask 添加简单的缓存支持  
- [flask-heroku-cacheify](https://github.com/rdegges/flask-heroku-cacheify) - 在 Heroku 上自动配置 Flask 缓存

## 数据验证

- [Flask-WTF](https://github.com/lepture/flask-wtf) - Flask 与 WTForms 的简单集成，支持 CSRF、防止文件上传攻击及 Recaptcha

## 邮件

- [Flask-Mail](https://github.com/mattupstate/flask-mail/) - 为 Flask 应用添加 SMTP 邮件发送功能

## 国际化 (i18n)

- [flask-babel](https://github.com/python-babel/flask-babel) - 基于 Babel 和 pytz 的 Flask 国际化和本地化支持

## 全文搜索

- [SQLAlchemy-Searchable](https://github.com/kvesteri/sqlalchemy-searchable) - Flask-SQLAlchemy 的全文搜索（仅支持 Postgres）  
- [flask_msearch](https://github.com/honmaple/flask-msearch) - Flask 的全文搜索，基于 Whoosh

## 限流

- [Flask-Limiter](https://github.com/alisaifee/flask-limiter) - 为 Flask 路由提供速率限制功能

## 任务队列

- [Flask-Dramatiq](https://flask-dramatiq.rtfd.io/) - Flask 的 Dramatiq 集成  
- [huey](https://github.com/coleifer/huey) - Python 轻量级任务队列  
- [Flask-RQ](https://github.com/mattupstate/flask-rq) - Flask 的 RQ (Redis Queue) 集成  
- [celery](https://github.com/celery/celery/) - 分布式任务队列

## 异常追踪

- [sentry-sdk](https://github.com/getsentry/sentry-python) - Python 客户端，用于 [Sentry](https://sentry.io/welcome/)  
- [airbrake-python](https://github.com/airbrake/airbrake-python) - Python 客户端，用于 [Airbrake](https://airbrake.io/)

## 链路追踪

- [flask-zipkin](https://github.com/qiajigou/flask-zipkin) - 基于 [Zipkin](https://zipkin.io/) 的分布式追踪  
- [Flask-OpenTracing](https://github.com/opentracing-contrib/python-flask) - 基于 [OpenTracing](http://opentracing.io/) 的分布式追踪

## APM

- [elastic-apm](https://github.com/elastic/apm-agent-python) - Elastic APM Python Agent

## 其他 SDK

- [Flask-GoogleMaps](https://github.com/rochacbruno/Flask-GoogleMaps) - 在 Flask 模板中构建和嵌入 Google Maps  
- [Flask-Gravatar](https://github.com/zzzsochi/Flask-Gravatar) - 在 Flask 中使用 Gravatar  
- [Flask-Pusher](https://github.com/iurisilvio/Flask-Pusher) - Flask 的 Pusher 集成  
- [Flask-Azure-Storage](https://github.com/alejoar/Flask-Azure-Storage) - Flask 与 Azure Storage 集成的扩展

## 前端

- [Flask-CORS](https://github.com/corydolphin/flask-cors) - 处理跨域资源共享（CORS），支持跨域 AJAX  
- [flask-assets](https://github.com/miracle2k/flask-assets) - Flask Webassets 集成  
- [flask-s3](https://github.com/e-dard/flask-s3) - 从 Amazon S3 无缝提供 Flask 静态资源  
- [Flask-SSLify](https://github.com/kennethreitz/flask-sslify) - 强制 Flask 应用使用 SSL  
- [Flask-HTMLmin](https://github.com/hamidfzm/Flask-HTMLmin) - Flask HTML 压缩器

## 开发（调试/测试/文档）

- [Flasgger](https://github.com/rochacbruno/flasgger) - 使用 Swagger 2.0 为 Flask 视图创建 API 文档  
- [flask-apispec](https://github.com/jmcarp/flask-apispec) - Flask 自文档 API  
- [flask2postman](https://github.com/numberly/flask2postman) - 从 Flask 应用生成 Postman 集合  
- [flask_profiler](https://github.com/muatik/flask-profiler) - Flask 路由分析器/性能分析  
- [Flask-DebugToolbar](https://github.com/mgood/flask-debugtoolbar) - Django 调试工具栏移植到 Flask  
- [flask-debug-toolbar-mongo](https://github.com/cenkalti/flask-debug-toolbar-mongo) - Flask Debug Toolbar 的 MongoDB 面板  
- [Flask-Testing](https://github.com/jarus/flask-testing) - Flask 单元测试扩展  
- [pytest-flask](https://github.com/pytest-dev/pytest-flask) - 用于测试 Flask 应用的 pytest fixture  
- [Flask-MonitoringDashboard](https://github.com/flask-dashboard/Flask-MonitoringDashboard) - 自动监控 Flask/Python Web 服务性能  
- [nplusone](https://github.com/jmcarp/nplusone#flask-sqlalchemy) - 自动检测 Flask+SQLAlchemy 的 N+1 查询  
- [connexion](https://github.com/zalando/connexion) - 基于 Flask 的 Swagger/OpenAPI 优先框架，支持自动端点验证和 OAuth2

## 工具类 (Utils)

- [flask-marshmallow](https://github.com/marshmallow-code/flask-marshmallow) - Flask + Marshmallow 美化 API  
- [flask-jsonrpc](https://github.com/cenobites/flask-jsonrpc) - Flask JSON-RPC 基础实现  
- [Flask-Bcrypt](https://github.com/maxcountryman/flask-bcrypt) - Flask bcrypt 哈希工具  
- [Mixer](https://github.com/klen/mixer) - 生成 Django 或 SQLAlchemy 模型实例  
- [Flask-FeatureFlags](https://github.com/trustrachel/Flask-FeatureFlags) - 根据配置启用或禁用功能  
- [Flask-Reggie](https://github.com/rhyselsmore/flask-reggie) - Flask URL 路由的正则转换器  
- [Flask-SocketIO](https://github.com/miguelgrinberg/Flask-SocketIO) - Flask Socket.IO 集成  
- [Flask-Moment](https://github.com/miguelgrinberg/Flask-Moment) - Flask 模板中的日期时间格式化（使用 moment.js）  
- [Flask-Paginate](https://github.com/lixxu/flask-paginate) - Flask 分页支持  
- [Flask-graphql](https://github.com/graphql-python/flask-graphql) - 为 Flask 应用添加 GraphQL 支持

# 资源
## 教程

- [如何构建一个几乎不花钱且永不宕机的新闻应用](http://blog.apps.npr.org/2013/02/14/app-template-redux.html) (NPR)  
- [使用 Flask 构建 Python 网站](http://maximebf.com/blog/2012/10/building-websites-in-python-with-flask/)  
- [Flask Mega-Tutorial](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)  
- [使用 Python & Flask 实现 RESTful Web API](http://blog.luisrei.com/articles/flaskrest.html)  
- [Discover Flask - 全栈开发](https://github.com/realpython/discover-flask)  
- [Flaskr - Flask 入门、TDD 和 jQuery](https://github.com/mjhea0/flaskr-tdd)

## 课程

- [Full Stack Foundations](https://www.udacity.com/course/full-stack-foundations--ud088)  
- [Designing RESTful APIs](https://www.udacity.com/course/designing-restful-apis--ud388)

## 书籍

- [Explore Flask](https://exploreflask.com/en/latest/)  
- [Flask Web Development](http://shop.oreilly.com/product/0636920031116.do)  
- [Real Python](https://realpython.com)  
- [Learning Flask Framework](https://www.packtpub.com/web-development/learning-flask-framework)  
- [Flask Blueprints](https://www.packtpub.com/web-development/flask-blueprints)  
- [Flask Framework Cookbook](https://www.packtpub.com/web-development/flask-framework-cookbook)  
- [Mastering Flask](https://www.packtpub.com/web-development/mastering-flask)  
- [Building Web Applications with Flask](https://www.packtpub.com/web-development/building-web-applications-flask)

## 幻灯片

- [用 Flask 创建漂亮的 REST API](http://pycoder.net/bospy/presentation.html)  
- [高级 Flask 模式](https://speakerdeck.com/mitsuhiko/advanced-flask-patterns)  
- [Flasky Goodness](https://speakerdeck.com/kennethreitz/flasky-goodness)  
- [领域驱动设计（Flask 实践）](https://speakerdeck.com/mikedebo/domain-driven-design-dot-dot-dot-with-flask)  
- [In Flask we Trust](https://speakerdeck.com/playpauseandstop/in-flask-we-trust)

## 视频

- [PyVideo](https://pyvideo.org/search.html?q=flask)  
- [Practical Flask Web Development Tutorials](https://www.youtube.com/playlist?list=PLQVvvaa0QuDc_owjTbIY4rbgXOFkUYOUB)

## Flask 实例项目

- [zmusic-ng](https://git.zx2c4.com/zmusic-ng/) - 音乐播放与下载 Web 界面  
- [GuitarFan](https://github.com/lowrain/GuitarFan) - 吉他谱  
- [June](https://github.com/pythoncn/june) - Python 社区项目  
- [Zerqu](https://github.com/lepture/zerqu) - 内容 API 平台  
- [motiky](https://github.com/notedit/motiky)  
- [missing](https://github.com/notedit/missing) - missing 列表服务  
- [thenewsmeme.com](https://github.com/danjac/newsmeme)  
- [overholt](https://github.com/mattupstate/overholt) - Flask 示例应用  
- [pypress](https://github.com/laoqiu/pypress) - Flask 团队博客  
- [thepast.me](https://github.com/laiwei/thepast)  
- [redispapa](https://github.com/no13bus/redispapa) - Flask + Angular + Socket.IO Redis 监控  
- [flaskblog](https://github.com/defshine/flaskblog) - 简单博客系统  
- [cleanblog](https://github.com/defshine/cleanblog) - Flask + MongoEngine 的博客系统  
- [Quokka CMS](https://github.com/rochacbruno/quokka) - Flask + MongoDB CMS  
- [chat](https://github.com/lzyy/chat) - 实时聊天系统（Flask + Gevent + APScheduler + Redis）  
- [chatapp](https://github.com/vinceprignano/chatapp) - Flask + Angular.js 聊天应用（Socket.IO）  
- [Frozen-Flask](https://github.com/Frozen-Flask)

