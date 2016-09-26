# <center>Java EE 程序设计</center>
# <center>教学基本要求</center>

### 1. `JSP` 编程基础
- `JSP` 注释 **`掌握`**
    - `HTML` 注释 **`掌握`**
    - `JSP` 的隐藏注释 **`掌握`**
- `JSP` 模板元素 **`掌握`**
- `JSP` 指令元素
    - `page` 指令 **`掌握`**
    - `taglib` 指令 **`掌握`**
    - `include` 指令 **`掌握`**
- `JSP` 脚本元素 **`掌握`**
    - `JSP` 声明
    - `JSP` 小脚本
    - `JSP` 表达式
- `JSP` 动作元素 **`了解`** 
- `JSP` 与`Servlet` 的内在关系 **`理解`**
- `XML` 文件结构和使用 **`了解`**

### 2. `JSP` 隐式对象
- `out` 对象
  - `print`  **`掌握`**
  - `println`  **`掌握`**
  - `clear`  **`了解`**
  - `flush`  **`了解`**
  - `close`  **`了解`**
- `request` 对象
  - `getParameter`  **`掌握`**
  - `setAttribute`  **`掌握`**
  - `getAttribute`  **`掌握`**
  - `getParameter` 与`getAttribute` 的区别 **`理解`**
  - `getRequestDispatcher.forward`  **`掌握`**
- `response` 对象
  - `sendRedirect`  **`掌握`**
  - `forward` 与 `sendRedirect` 的区别 **`理解`**
- `session` 对象
  - `setAttribute`  **`掌握`**
  - `getAttribute`  **`掌握`**
  - `session` 和`request` 的 `getAttribute` 方法的区别 **`理解`**
- `application` 对象
  - `getServletContext` **`理解`**
- `exception` 对象
  - `JSP` 页面异常信息的处理 **`了解`**
  - `errorPage` 属性 **`了解`**
  - `isErrorPage` 属性 **`了解`**
- `pageContext` 对象
  - `getAttribute` **`了解`**
  - `setAttribute` **`了解`**
- `page` 对象 **`了解`**
- `config` 对象 **`了解`**

### 3. `Servlet` 编程
- `Servlet` 的运行机制 **`理解`**
- `Servlet` 的配置
  - `Servlet` 的注册 **`掌握`**
  - `Servlet` 的映射配置 **`掌握`**
- `Servlet` 的生命周期
  - `init` **`理解`**
  - `service` **`理解`**
  - `destroy` **`理解`**	
- `Servlet` 处理表单提交数据的方式
  - `doGet` **`掌握`**
  - `doPost` **`掌握`**
  - `get` 请求和 `post` 请求的区别 **`掌握`**
- `cookie` 的使用 **`较高要求`**
- 会话跟踪
  - `session id` 的使用 **`理解`**
  - 使用`session` 进行会话跟踪 **`掌握`**
    - `setAttribute` 
    - `getAttribute` 
    - `removeAttribute` 
    - `invalidate` 
    - `isNew` 
    - `getLastAccessedTime` 
    - `getMaxInactiveInterval` 
  - 使用`ServletContext` 进行会话跟踪 **`较高要求`**
  
### 4. `EL` 表达式语言 和 `JSTL` 标签库 
- `JSTL` 的由来 **`了解`**
  - `JSTL` 与 `EL` 的关系 **`了解`**
  - `EL` 表达式
    - `EL` 表达式从四种作用域范围取值的方法 **`掌握`**
    - `EL` 读取表单提交数据的方法 **`掌握`**
    - `EL` 表达式中 `.` 与 `[]` 运算符的区别 **`掌握`**
    - `EL` 表达式的算术运算符 **`掌握`**
    - `EL` 表达式的关系运算符 **`掌握`**
    - `EL` 表达式的逻辑运算符 **`掌握`**
- `JSTL` 的 `Core` 标签库
  - `c:forEach` **`掌握`**
  - `c:if` **`掌握`**
  - `c:choose` **`掌握`**
  - `c:when` **`掌握`**
  - `c:otherwise` **`掌握`**
- `functions` 标签库 **`较高要求`**
- `fmt` 标签库 **`较高要求`**
- 开发自定义标签 **`较高要求`**

### 5. 过滤器和监听器
- 过滤器的生命周期
  - `init`  **`理解`**
  - `doFilter` **`掌握`**
  - `destroy`  **`理解`**
- 过滤器的配置
  - 在 `web.xml` 中注册和配置过滤器 **`掌握`**
  - 配置过滤器的初始化参数 **`掌握`**
  - 多个过滤器的过滤顺序 **`了解`**
  - 一个过滤器对多个资源过滤的配置 **`了解`**
- 常用过滤器
  - 配置编码过滤器 **`掌握`**
  - 配置权限验证过滤器 **`理解`**
- 常用监听器
  - 用于处理会话事件的监听器接口 **`掌握`**
    - `HttpSessionListener` 
    - `HttpSessionAttributesListener` 
  - 用于处理`ServletContext` 事件的监听器接口 **`了解`**
    - `ServletContextListener` 
    - `ServletContextAttributesListener` 
    
### 6. `JDBC` 编程
- `JDBC` 种类
  - 本地 `API` 驱动 **`了解`**
  - 网络协议驱动 **`了解`**
  - 本地协议驱动 **`了解`**
- `JDBC` 连接数据库 **`掌握`**
- 常用 `JDBC` 类和方法
  - 加载数据库驱动 `Class.forName` **`掌握`**
  - 创建数据库连接 `DriverManager.getConnection` **`掌握`**
  - 创建 `Statement` 或 `PreparedStatement` 对象 **`掌握`**
  - 执行查询返回结果集 `ResultSet` 对象 **`掌握`**
  - 常用的关闭方法 `close` **`掌握`**
- 可滚动结果集
  - `createStatement` **`了解`**
  - `ResultSet` 的结果集滚动方法： **`了解`**
    - `first` 
    - `last` 
    - `beforeFirst` 
    - `afterLast` 
    - `relative` 
    - `absolute` 
- 可更新结果集
  - `createStatement`  **`了解`**
  - `ResultSet` 的结果集更新方法 **`了解`**
    - `updateType` 
    - `updateRow` 
- `JDBC` 调用存储过程 **`较高要求`**
- 事务处理
  - 提交 `commit` **`掌握`**
    - `setAutoCommit` 
    - `getAutoCommit` 
  - 回滚 `rollback` **`掌握`**
- 批处理
  - `addBatch`  **`了解`**
  - `executeBatch`  **`了解`**
- 操纵 `BLOB` /`CLOB` 数据类型 **`较高要求`**
- 使用 `JDBC` 获取元数据 **`了解`**

### 7. `jQuery` `JS` 库
- `jQuery` 简介 **`了解`**
- `jQuery` 就绪方法 **`掌握`**
- `jQuery` 的选择器 **`掌握`**
- `jQuery` 的事件处理 **`掌握`**
- `jQuery` 的效果 **`掌握`**
- `jQuery` 的 `HTML` 操作 **`掌握`**
- `jQuery` 的 `AJAX` 实现方式
  - `$.post`  **`理解`**
  - `$.get`  **`了解`**
  - `$.ajax`  **`掌握`**
- 常用的 `jQuery` 插件的使用 **`较高要求`**

### 8. `JSON` 数据交换格式
- `JSON` 的数据结构 **`掌握`**
- 常用的 `JSON` 库 **`掌握`**