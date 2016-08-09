# <center>Java EE 轻量级框架技术</center>
# <center>教学基本要求</center>

###  1. `MVC` 设计模式
- `JSP` 设计模式
  - `JSP`  `Model` 1架构 **`理解`**
  - `JSP`  `Model` 2架构 **`理解`**
- `MVC` 设计模式
  - `Model`  **`理解`**
  - `View`  **`理解`**
  - `Controller`  **`理解`**
- 常用的`MVC` 设计模式框架
  - `Struts`  **`理解`**
  - `WebWork`  **`了解`**
  - `Struts` 2 **`了解`**
  
###  2. `Struts` 基础
- `Struts` 项目简介 **`了解`**
- `Struts` 的安装 **`理解`**
- 开发第一个`Struts` 应用程序 **`掌握`**

###  3. `Struts` 核心组件
- 中央控制器`ActionServlet` 
  - `ActionServlet` 的作用 **`掌握`**
  - `ActionServlet` 类的`doGet` ()方法和`doPost` ()方法 **`理解`**
  - `ActionServlet` 类的`process` ()方法 **`理解`**
  - `Struts` 的`Processor` 类简介 **`理解`**
  - `ActionServlet` 类在`web` .`xml` 文件中的配置 **`掌握`**
- `ActionForm` 类
  - `ActionForm` 类的作用 **`掌握`**
  - `ActionForm` 类的作用时间 **`掌握`**
 - `Action` 类/`ActionForward` 类/`ActionMapping` 类
  - `Action` 类在`Struts` 项目中的作用 **`掌握`**
  - `Action` 类中的`execute` 方法的具体实现 **`掌握`**
  - `ActionForward` 类的作用和常用方法 **`掌握`**
  - `ActionMapping` 类的作用和常用方法 **`掌握`**
- `Strut` 配置文件`struts` -`config` .`xml` 
  - `Struts` -`config` .`xml` 配置文件的作用 **`理解`**
  - `Struts` 配置文件的基本结构 **`理解`**
  - `Struts` 配置文件的常用元素 **`掌握`**
  - `Struts` 配置文件的<`form` -`bean` >元素的配置及各属性含义 **`掌握`**
  - `Struts` 配置文件的<`action` >元素的配置及各属性含义 **`掌握`**
- `Struts` 各组件与`MVC` 设计模式的各组件的对应关系 **`理解`**

###  4. `Struts` 国际化处理
- `Struts` 国际化的含义和作用 **`了解`**
- 资源文件和资源包
  - 资源文件的作用 **`理解`**
  - 资源文件在`struts` -`config` .`xml` 中的配置 **`掌握`**
  - 不同语言资源文件的命名特点 **`掌握`**
  - 资源文件的转码实现 **`掌握`**
  - `native` 2`ascii` 命令的使用 **`掌握`**
- `Struts` 国际化的实现
  - `bean` 标记库的基本使用 **`掌握`**
  - 资源文件的创建和配置 **`掌握`**
  
###  5. `Struts` 动态表单验证
- 普通表单验证的实现
  - `FormBean` 的`validate` ()方法的重写 **`掌握`**
  - `ActionErrors` 类的`add` 方法 **`掌握`**
  - `ActionMessages` 类的使用 **`掌握`**
  - `Struts` 的`html` 标记在表单验证中的作用 **`掌握`**
  - 表单验证在`Struts` 配置文件中需要的修改 **`掌握`**
- `Struts` 动态表单
  - 动态表单的优点和作用 **`理解`**
  - `DynaActionFrom` 类 **`掌握`**
  - 动态表单的配置 **`掌握`**
- `Struts` 的`Validator` 验证插件的使用
  - 动态表单与验证插件的关系 **`理解`**
  - 验证插件类及其在`struts` -`config` .`xml` 中的配置 **`掌握`**
  - `DynaValidatorForm` 类 **`掌握`**
  - 使用验证插件时`Action` 类的修改 **`掌握`**
  - `Validator` -`rules` .`xml` 文件的内容和作用 **`掌握`**
  - 常用的验证错误信息 **`掌握`**
  - `Validation` .`xml` 文件和常用元素的配置 **`掌握`**
  - 使用`Validator` 验证插件的一般步骤 **`理解`**
  
###  6. `Struts` 标记库
- `Struts` 的`html` 标记库
  - `Html` 标记库中常用标记的使用 **`掌握`**
  - `Struts` 错误标记的使用 **`掌握`**
  - 表单标记的使用及<`html` :`form` >标记的特殊作用 **`掌握`**
- `Struts` 的`bean` 标记库
  - 消息标记 **`掌握`**
  - 变量定义标记 **`掌握`**
  - 显示属性标记 **`掌握`**
- `Struts` 的`logic` 标记库
  - 条件逻辑标记 **`掌握`**
  - 重复逻辑标记 **`掌握`**
  - 流程控制逻辑标记 **`掌握`**
- `Struts` 的`tiles` 标记 **`了解`**

###  7. `Struts` 2基础
- `Struts` 2框架简介 **`了解`**
- `Struts` 2的安装 **`理解`**
- 开发第一个`Struts` 2应用程序 **`掌握`**

###  8. `Struts` 2进阶
- `Struts` 2的拦截器 **`较高要求`**
-  `OGNL` 简介 **`较高要求`**

###  9. `Hibernate` 基础
- `Hibernate` 项目简介
  - `ORM` 原理 **`理解`**
  - `Hibernate` 的`ORM` 实现机制 **`理解`**
- `Hibernate` 的安装 
  - `Hibernate` 的常用包 **`理解`**
-  第一个`Hibernate` 项目
  - `Hibernate` 常用组件 **`掌握`**
  - `ORM` 的具体实现 **`理解`**
  
###  10. `Hibernate` 核心组件
-  持久化类
  - 持久化类的定义 **`了解`**
  - 持久化类的作用 **`理解`**
  - 持久化类的生命周期 **`掌握`**
-  `Hibernate` 配置文件
  - 配置文件的两种类型 **`理解`**
  - 配置文件的作用 **`理解`**
  - 常用的`Hibernate` 配置属性 **`掌握`**
-  `Hibernate` 的映射文件
  - 映射文件的作用 **`理解`**
  - 映射文件的常用元素及其属性的配置 **`掌握`**
  - 映射文件在`Hibernate` 配置文件中的配置 **`掌握`**
-  `Hibernate` 的常用类和接口
  - `Configuration` 类及常用方法 **`掌握`**
  - `SessionFaction` 接口及常用方法 **`掌握`**
  - `Session` 接口及常用方法 **`掌握`**
  - `Query` 接口及常用方法 **`掌握`**
  - `Transaction` 接口及常用方法 **`掌握`**
  
###  11. `Hibernate` 数据查询
- `HQL` 查询方式
  - `HQL` 与`SQL` 的本质区别 **`理解`**
  - 常用查询的`HQL` 实现 **`掌握`**
  - 命名`HQL` 查询 **`掌握`**
- `QBC` 查询
  - `Criteria` 查询方式的特点 **`理解`**
  - 常用查询的实现 **`掌握`**
- `Native`  `SQL` 查询
  - `NativeSQL` 查询的特点 **`理解`**
  - 命名`NativeSQL` 查询 **`掌握`**
  
###  12. `Hibernate` 关联映射
- 一对一外键关联映射 **`掌握`**
- 一对一主键关联映射 **`掌握`**
- 一对多/多对一关联映射 **`掌握`**
- 第三方表的关联映射 **`掌握`**
- 单向关联与双向关联 **`掌握`**

###  13. `Hibernate` 缓存与事务
- 一级`Cache`  **`掌握`**
- 二级`Cache`  **`掌握`**
- `Hibernate` 编程式事务管理 **`掌握`**
- `Hibernate` 声明式事务管理 **`掌握`**

###  14. `Spring` 基础
- `Spring` 项目简介 **`了解`**
- 一个`Spring` 入门实例 **`掌握`**

###  15. `Spring` 的`IoC` 实现
- `IoC` 的概念
  - `IoC` 的特点 **`理解`**
  - `IoC` 的三种实现方式及优缺点 **`掌握`**
  - 控制反转和依赖注入的概念 **`理解`**
- `Spring` 的`IoC` 的实现
  - `Spring` 的配置文件的作用 **`理解`**
  - `IoC` 三种实现方式在`Spring` 中的具体体现 **`掌握`**
- `Spring` 的核心组件
  - `Spring` 容器的实例化 **`掌握`**
  - `Bean` 的实例化 **`掌握`**
  
###  16. `Spring` 的`AOP` 实现
- `AOP` 的基本概念
  - 切面的概念 **`理解`**
  - `AOP` 的特点及优点 **`理解`**
  - `AOP` 的实现种类与`Spring` 的`AOP` 实现 **`掌握`**
- `Spring` 的通知类型
  - `Before` 通知 **`较高要求`**
  - `After` 通知 **`较高要求`**
  - `Throws` 通知 **`较高要求`**
- `AOP` 联盟的`Around` 通知 **`较高要求`**
- `Spring` 的静态切入点
  - 静态切入点的概念 **`较高要求`**
  - `NameMatchMethodPointcutAdvisor` 类 **`较高要求`**
  - `RegexpMethodPointcutAdvisor` 类 **`较高要求`**
- `Spring` 的动态切入点 **`较高要求`**
- `Introduction` 
  - 使用`DelegatingIntroductionInterceptor` 类 **`较高要求`**
  - 自动代理 **`较高要求`**
  - `DefaultAdvisorAutoProxyCreator`  **`较高要求`**
  
###  17. `Spring` 的数据访问
- `Spring` 对`DAO` 的支持
  - `DAO` 的概念 **`理解`**
  - 一致的异常层次 **`掌握`**
  - 一致的`DAO` 抽象类 **`掌握`**
- 在`Spring` 中使用`JDBC` 
  - 使用`JdbcTemplate`  **`掌握`**
  - `JDBC` 操作的`Java` 对象化 **`掌握`**
  
###  18. `Spring` 与`Hibernate` 的整合
-  `Spring` 和`Hibernate` 的整合 **`掌握`**
- `SessionFactory` 的注入 **`掌握`**
- `HibernateTemplate` 类的常用方法 **`掌握`**
- `HibernateDAOSupport` 类的常用方法 **`掌握`**
- `HibernateTemplate` 的分页实现 **`较高要求`**

###  19. `Spring` 事务管理
- 事务的概念
  - 编程式事务管理 **`理解`**
  - 声明式事务管理 **`理解`**
- `JDBC` 编程事务管理
  - 使用`TransactionTemplate`  **`掌握`**
  - 使用`PlatformTransactionManager`  **`掌握`**
- `JDBC` 声明式事务管理 **`掌握`**

###  20. `Spring` 与`Struts` 的整合
- `Spring` 与`Struts` 整合
  - 整合的意义 **`理解`**
  - 整合的三种基本方式及其优缺点 **`理解`**
- 使用`DelegatingActionProxy` 类实现整合
  - `ContextLoaderPlugIn` 类在`Struts` 中的配置 **`掌握`**
  - `DelegatingActionProxy` 类的作用 **`理解`**
  - `Spring` 中配置请求和`Action` 类 **`掌握`**
  - 在`Action` 类中应用`Spring` 的`IoC` 功能 **`掌握`**
-  使用`DelegatingActionProcessor` 类实现整合 **`理解`**
-  使用`ActionSupport` 实现整合 **`理解`**

###  21. `Spring` 的`MVC` 框架
- `SpringWebMVC` 框架的基本构成
  - `DispatcherServlet` 类的作用 **`理解`**
- `WebApplicationContext` 
  - 使用`ContextLoadListener`  **`理解`**
  - 使用`ContextLoadServlet`  **`理解`**
  
###  22. `Spring` 的其他组件应用
- 在`Spring` 中使用`JavaMail`  **`较高要求`**
- `SpringRMI` 入门 **`较高要求`**

###  23. `SSH` 项目的整合开发
- `SSH` 整合项目的基本运行流程 **`掌握`**
- 在`MyEclipse` 中搭建基于`SSH` 架构的`Web` 应用程序 **`掌握`**

