
# FuAdmin

[![img](https://img.shields.io/badge/license-Apache%202.0-dark)](https://gitee.com/fuadmin/fu-admin/blob/master/LICENSE) [![img](https://img.shields.io/badge/python-%3E=3.7.x-green.svg)](https://python.org/) [![PyPI - Django Version badge](https://img.shields.io/badge/django%20versions-4.0-blue)](https://docs.djangoproject.com/zh-hans/4.0.4/) [![img](https://img.shields.io/badge/node-%3E%3D%2016.0.0-brightgreen)](https://nodejs.org/zh-cn/) [![img](https://gitee.com/fuadmin/fu-admin/badge/star.svg?theme=dark)](https://gitee.com/fuadmin/fu-admin) [![GitHub stars](https://img.shields.io/github/stars/FuAdmin/FuAdmin.svg?theme=dark&label=Github)](https://github.com/FuAdmin/FuAdmin)

- 官方文档：[http://124.222.210.96](http://124.222.210.96)
- 中文预览：[http://124.222.210.96:8080](http://124.222.210.96:8080)
- English Preview：[http://124.222.210.96:9090](http://124.222.210.96:9090)

💡 **「前端 」**

Vue-Vben-Admin 是一个基于 Vue3.0、Vite、 Ant-Design-Vue、TypeScript 的后台解决方案，目标是为开发中大型项目提供开箱即用的解决方案。包括二次封装组件、utils、hooks、动态菜单、权限校验、按钮级别权限控制等功能。项目会使用前端较新的技术栈，可以作为项目的启动模版，以帮助你快速搭建企业级中后台产品原型。也可以作为一个示例，用于学习 vue3、vite、ts 等主流技术。该项目会持续跟进最新技术，并将其应用在项目中。

💡 **「后端 」**

- 👭 后端采用 Python 语言 Django 框架以及强大的 [Django Ninja](https://django-ninja.rest-framework.com/)。
- 💡 支持加载动态权限菜单，多方式轻松权限控制。

##  「Django Ninja」  VS 「Django REST framework」

### Django Ninja:

1. **异步支持：** Django Ninja 支持异步请求处理，这意味着它可以处理大量的并发请求而不阻塞服务器。
2. **文档生成：** Django Ninja 自带了一个自动生成的交互式 API 文档（Swagger UI），这有助于开发者更容易地测试和了解 API。
3. **轻量级：** Django Ninja 被设计为一个轻量级框架，提供了一些简化开发的功能，如自动生成的 OpenAPI 和 JSON Schema 文档。
4. **Pydantic 集成：** Django Ninja 使用 Pydantic 进行数据验证和序列化，这使得定义和验证数据模型变得更加简单。
5. **速度：** 由于异步支持和一些优化，Django Ninja 在性能上可能更高效。

### Django REST framework (DRF):

1. **成熟度：** DRF 是一个成熟且广泛使用的框架，拥有大量的文档、社区支持和可用的扩展。
2. **功能丰富：** DRF 提供了许多功能，包括身份验证、权限、序列化、视图集等，使其成为构建复杂 API 的理想选择。
3. **社区支持：** DRF 拥有强大的社区，有很多资源和插件可以使用，使开发变得更加容易。
4. **可扩展性：** DRF 提供了许多可扩展的选项，可以根据项目的需要进行定制。
5. **广泛应用：** DRF 被许多大型项目和企业广泛应用，它的可用性和稳定性在生产环境中得到验证。

**选择Django ninja要点：**

- 如果你注重性能、轻量级和异步支持，并且喜欢自动生成的 API 文档，可以选择 Django Ninja。
- 学习难度 Django-Ninja:Django Rest framework我认为是100:1,  Django Ninja易上手,而且可以实现Django Rest framework+对应生态的所有功能
- **Pydantic 集成：** Django Ninja 使用 Pydantic 进行数据验证和序列化，这使得定义和验证数据模型变得更加简单()

## 内置功能

1. 👨‍⚕️ 菜单管理：配置系统菜单，操作权限，按钮权限标识、后端接口权限等。
2. 🧑‍⚕️ 部门管理：配置系统组织机构（公司、部门、角色）。
3. 👩‍⚕️ 角色管理：角色菜单权限分配、数据权限分配、设置角色按部门进行数据范围权限划分。
4. 🧑‍🎓 权限权限：授权角色的权限范围。
5. 👨‍🎓 用户管理：用户是系统操作者，该功能主要完成系统用户配置。
6. 🧑‍🔧 数据字典：对系统中经常使用的一些较为固定的数据进行维护。
7. 🧑‍🔧 分类字典：对系统中经常使用的一些树形数据进行维护。
8. 📁 附件管理：对平台上所有文件、图片等进行统一管理。
9. 🗓️ 操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10. 定时任务：系统设置定时任务。

