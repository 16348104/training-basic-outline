# <center>Java EE 轻量级框架技术</center>
# <center>教学基本要求</center>

###  1. `MyBatis` 基础
- `MyBatis` 项目简介 **`了解`**
- `MyBatis` 与 `Hibernate` 的比较 **`理解`** 
-  第一个`MyBatis` 项目
  - `MyBatis` 核心组件 **`掌握`**
    - `mapper file`
    - `configuration file`
    - `mapper interface`
    - `SqlSessionFactory`
    - `SqlSession`
  - `MyBatis` 的两种实现方式 **`掌握`**
    - 接口实现
    - `mapper` 实现
  
###  2. `MyBatis` 核心组件
- `MyBatis` 的配置文件
  - 配置文件的作用 **`理解`**
  - 配置文件的常用元素及其属性的配置 **`掌握`**
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
  
###  3. `MyBatis` 关联映射
- 一对一关联映射 **`掌握`**
- 一对多/多对一关联映射 **`掌握`**
- 多对多第三方表的关联映射 **`掌握`**

###  4. `MyBatis` 动态 `SQL`
- `if` **`掌握`**
- `choose` **`掌握`**
- `where` **`掌握`**
- `trim` **`掌握`**
- `foreach` **`掌握`**
- `set` **`掌握`**

###  5. `Spring` 基础
- `Spring` 项目简介 **`了解`**
- 一个 `Spring` 入门实例 **`掌握`**

###  6. `Spring` 的 `IoC` 与 `DI`
- `IoC` 的概念
  - `IoC` 的特点 **`理解`**
  - `IoC` 的三种实现方式及优缺点 **`掌握`**
  - `IoC` 与 `DI` 的关系 **`理解`**
- `Spring` 的 `IoC` 的实现
  - `Spring` 的配置文件的作用 **`理解`**
  - `IoC` 三种实现方式在 `Spring` 中的具体体现 **`掌握`**
- `Spring` 的核心组件
  - `Spring` 容器的实例化 **`理解`**
  - `Bean` 的实例化 **`理解`**
 
###  7. `Spring` 的 `MVC` 框架
- `SpringWebMVC` 框架的基本构成
  - `DispatcherServlet` 类的作用 **`理解`**
- `WebApplicationContext` 
  - 使用 `ContextLoadListener` **`理解`**
  - 使用 `ContextLoadServlet` **`理解`**
  
###  8. `Spring` 与 `MyBatis` 的整合
- `Spring` 和 `Mybatis` 的整合 **`掌握`**
- `dataSource` 的注册 **`掌握`**
- `sqlSessionFactory` 的注入 **`掌握`**
- `sqlSession` 的注入 **`掌握`**

###  9. `Spring` 的事务管理
- 事务的概念
  - 编程式事务管理 **`理解`**
  - 声明式事务管理 **`理解`**
- `JDBC` 编程事务管理
  - 使用`TransactionTemplate` **`掌握`**
  - 使用`PlatformTransactionManager` **`掌握`**
- `JDBC` 声明式事务管理 **`掌握`**
  
### 10. `Java EE` 轻量级框架项目架构
- 分层
    - `DAO` 层 **`理解`**
    - `Service` 层 **`理解`**
- 泛型化 **`理解`**
- 模板与自动工具类的创建和使用 **`掌握`**

###  11. `Spring` 的`AOP` 实现
- `AOP` 的基本概念
  - 切面的概念 **`理解`**
  - `AOP` 的特点及优点 **`理解`**
  - `AOP` 的实现种类与 `Spring` 的 `AOP` 实现 **`掌握`**
- `Spring` 的通知类型
  - `Before` 通知 **`较高要求`**
  - `After` 通知 **`较高要求`**
  - `Throws` 通知 **`较高要求`**
- `AOP` 联盟的 `Around` 通知 **`较高要求`**
- `Spring` 的静态切入点
  - 静态切入点的概念 **`较高要求`**
  - `NameMatchMethodPointcutAdvisor` 类 **`较高要求`**
  - `RegexpMethodPointcutAdvisor` 类 **`较高要求`**
- `Spring` 的动态切入点 **`较高要求`**
- `Introduction` 
  - 使用 `DelegatingIntroductionInterceptor` 类 **`较高要求`**
  - 自动代理 **`较高要求`**
  - `DefaultAdvisorAutoProxyCreator` **`较高要求`**

###  12. `Spring` 的其他组件应用
- `Spring` 中使用 `JavaMail` **`较高要求`**
- `Spring` 定时任务 **`较高要求`**
- `SpringRMI` 入门 **`较高要求`**
