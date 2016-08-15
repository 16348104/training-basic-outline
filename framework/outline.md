# <center>Java EE 轻量级框架技术</center>
# <center>教学基本要求</center>

###  9. `MyBatis` 基础
- `MyBatis` 项目简介
- `MyBatis` 与 `Hibernate` 的比较 
-  第一个`MyBatis` 项目
  - `MyBatis` 核心组件 **`掌握`**
    - `mapper file`
    - `configuration file`
    - `mapper interface`
    - `SqlSessionFactory`
    - `SqlSession`
  - `MyBatis` 的两种实现方式
    - 接口实现
    - `mapper` 实现
  
###  10. `MyBatis` 核心组件
- `MyBatis` 的配置文件
  - 配置文件的作用
  - 配置文件的常用元素及其属性的配置
    - `environment`
    - `dataSource`
    - `transactionManager`
    - `properties`
    - `typeAliases`
    - `typeHandlers`
    - `settings`
    - `mappers`
- `MyBatis` 的映射文件
  - 映射文件的作用 **`理解`**
  - 映射文件的常用元素及其属性的配置 **`掌握`**
    - `mapper`
    - `insert`
      - `parameterType`
      - `useGeneratedKeys`
      - `keyProperty`
    - `update`
    - `delete`
    - `select`
      - `resultType`
      - `resultMap`
    - `resultMap`
      - `id`
      - `result`
      - `extends` `resultMap`  
-  `MyBatis` 的常用类和接口
  - `SqlSessionFactory` 接口及常用方法 **`掌握`**
  - `SqlSession` 类及常用方法 **`掌握`**
  
###  12. `Hibernate` 关联映射
- 一对一关联映射 **`掌握`**
- 一对多/多对一关联映射 **`掌握`**
- 多对多第三方表的关联映射 **`掌握`**

###  13. `MyBatis` 动态 `SQL`
- `if`  **`掌握`**
- `choose`
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

