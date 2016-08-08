# 网页设计基础教学基本要求


### 1. 网页设计开发环境与工具
- `WebStrom` 集成开发环境
  - 系统安装与配置 **`了解`**
  - 新建普通`HTML` 文件、`JS` 文件、`CSS` 文件 **`掌握`**
  - 编辑窗口的使用 **`掌握`**
  - 快捷键 **`掌握`**
- 普通文本编辑工具
  - `Notepad++` 工具或其他文本编辑工具编辑网页设计文件 **`掌握`**

### 2. `HTML` 语言编程
- `HTML` 语言基础知识 **`掌握`**
  - `HTML` 语言简介
  - `HTML` 语法基础
    - 标签
    - 属性
    - 元素
    - 文档
    - 注释
- `HTML` 编程基础 **`掌握`**
  - `HTML` 文档基本结构
    - `!DOCTYPE`
    - `HTML`
    - `HTML`
    - `HEAD`
    - `TITLE`
    - `META`
    - `BODY`
  - 段落 `p`
    - `br`
    - `wbr`
    - `hr`
  - 标题 `h1` ~ `h6`
  - 字体设置
  - 文字修饰 
    - `b`
    - `i`
    - `u`
    - `s` 
    - `big`
    - `small`
    - `sup`
    - `sub`
  - 列表
    - `ul`
      - `type`
      - `li`
    - `ol`
      - `type`
      - `start`
      - `li`
    - `dl`
      - `dt`
      - `dd`
  - `html` 实体
    - `&nbsp;`
    - `&gt;`
    - `&lt;`
    - `&amp;`
- 嵌入对象 **`掌握`**
  - 锚点 `a`
    - `href`
    - `url`
    - `target`
    - 站点链接
    - 页面中指定位置链接
    - 邮件链接
    - 图像链接
  - 图像 `img`
    - `src`
    - `alt`
    - `title`
    - `width`
    - `height`
    - `border`
    - `align`
    - 常用图像格式
     - `JPEG`
     - `GIF`
     - `PNG`
  - 表格 `table`
    - `tr`
    - `td`
    - `th`
    - `thead`
    - `tbody`
    - `tfoot`
   - `caption
  - 滚动字幕
  - 音频视频
    - `audio`
    - `video`
- 框架与布局设计 **`掌握`**
  - 框架集与框架 `frameset`
    - `cols`
    - `rows`
    - `border`
    - `bordercolor`
    - `frame`
    - `src`
  - 内联框架 `iframe`
    - `src`
    - `name`
    - `width`
    - `height`
- 表单与界面设计 **`掌握`**
  - 表单 `form` 
    - `autocomplete`
    - `novalidate` 
    - `name` 
    - `method`
    - `action`
  - 输入控件 `input`
    - `autocomplete`
    - `autofocus`   
    - `form`
    - `placeholder`
    - `height` 
    - `weight`  
    - `required`  
    - `pattern`
    - `regexp`
    - `list`
    - `name`
    - `type` 属性
      - `text`
      - `password`
      - `button`
      - `submit`
      - `reset`
      - `radio`
      - `checkbox`
      - `file`
      - `email`
      - `url`
      - `search`
      - `telephone`
      - `calendar`
      - `date` `month` `week` `time` `datetime` `datetime-local`
      - `color`
      - `range` `number` `min` `max` `step`
  - 列表选择域 `select`
    - `name`
    - `size`
    - `option`
    - `selected`
  - 多行文本框 `textarea`
    - `name`
    - `rows`
    - `cols`
  - 控件说明
    - `label`
    - `fieldset`
    - `legend`
  - 新表单元素：
    - `datalist`
    - `keygen`
    - `output`
  - 对 `input` 元素新加的 `form` `overrides` 属性
    - `formaction`
    - `formenctype`
    - `formmethod`
    - `formnovalidate`
    - `formtarget`
- `HTML5` 其他新标签：
  - `article`
  - `header`
  - `footer`
  - `nav`
  - `section`
  - `aside`
  - `bdi`
  - `command`
  - `details` `summary`
  - `dialog`
  - `embed`
  - `figure` `figcaption`
  - `keygen`
  - `mark`
  - `meter`
  - `progress`
  - `rp`
  - `rt`
  - `ruby`
  - `time`
  - `track`
- `HTML5` 新加的全局属性：
  - `contenteditable`
  - `contextmenu`
  - `draggable`
  - `dropzone`
  - `hidden`
  - `spellcheck`
  - `translate`

### 3. `CSS` 样式表设计
- `CSS` 样式表基础知识 **` 掌握`**
  - `CSS` 起因及作用
  - `CSS` 类型及层叠次序
- `CSS` 语法规则
选择符 {属性 : 值 ;  …} 
注释、空格及大小写、选择符分组、子元素继承
- `CSS` 样式表基本语法 **` 了解`**
	- 内联式样式表（位于`body`和/`body`之间）
 选择符 `style`= “ 属性1: 值1; 属性2: 值2;  …” 
	- 文档级样式表（位于`head`和/`head`之间，对整个网页有效）
`style` `type`=”`text`/`css`”
	选择符 {属性1: 值1; 属性2: 值2; …}    …
/`style`
	- 外部样式表（.`css` 文件）
引用：`link` `rel`="`stylesheet`"  `type`=”`text`/`css`”  `href`=”样式表路径” 
引用：`style` `type`=”`text`/`css`”  @`import` `url`(样式表路径);  /`style`
	- 类选择符和`ID` 选择符的应用
- `CSS` 样式表属性及应用 **` 了解`**
	- 字体属性
`font` 、`font`-`family` 、`font`-`size` 、`font`-`style` 、`ont`-`weight`
	- 文本修饰属性
`text`-`indent` 、`text`-`align` 、`text`-`decoration`
`word`-`spacing` 、 `line`-`height`
	- 颜色与背景属性
`color` 、 `background`-`image`
	- 边框与滚动条属性
`border`-`color` 、 `border`-`width` 、 `border`-`style`
	- 链接显示属性
`a`:`link` 、 `a`:`visited` 、 `a`:`hover` 、 `a`:`active`
	- 定位属性
`position` 、`left` 和`top`、`width` 和`height` 、`overflow`
- `CSS` 滤镜功能 **` 了解`**
 (5)`CSS`3新特性 **` 掌握`**
	- `CSS`3 边框
`border`-`radius`、`box`-`shadow`、`border`-`image`
	- `CSS`3 背景
`background`-`size`、`background`-`origin`、`background`-`clip`
多个背景图像: `background`-`image`:`url`(`bg`_`flower`.`gif`),`url`(`bg`_`flower`_2.`gif`);
	- 文本属性
`hanging`-`punctuation`、`punctuation`-`trim`、`text`-`align`-`last`	、`text`-`emphasis`、`text`-`justify`、`text`-`outline`、`text`-`overflow`、`text`-`shadow`、`text`-`wrap`、`word`-`break`、`word`-`wrap`
- `CSS`3高级新特性 **` 较高要求`**
	- 字体
@`font`-`face`
	- 2`D` 转换
`translate`()、`rotate`()、`scale`()、`skew`()、`matrix`()
	- 3`D` 转换
`rotateX`()、`rotateY`()
	- 过渡属性
`Transition`、`transition`-`property`、`transition`-`duration`、`transition`-`timing`-`function`	、`transition`-`delay`
	- `CSS`3 动画
@`keyframes`、`animation`
	- 多列属性
`column`-`count`、`column`-`fill`、`column`-`gap`	、`column`-`rule`	、`column`-`rule`-* `column`-`rule`-`color`、`column`-`rule`-`style`、`column`-`rule`-`width`	、`column`-`span`、`olumn`-`width`、`columns`
	- `CSS`3 用户界面
`appearance`、`box`-`sizing`、`icon`、`nav`-`down`、`nav`-`index`	、`nav`-`left`、`nav`-`right`、`nav`-`up`、`outline`-`offset`、`resize`

### 4. `JavaScript` 语言编程
- `JavaScript` 基础知识 **` 掌握`**
	- `JavaScript` 语言概述
	- `JavaScript` 在网页设计中的作用
- `JavaScript` 基础语法 **` 掌握`**
	- 语句、代码、代码块
	- 基本数据类型、变量与常量
	- 常用运算符
算术运算符、比较运算符、逻辑运算符、字符串运算符
	- 流程控制语句
选择语句 （`if`）、分支语句 (`switch`)
循环语句：`For` 语句（`For` `in`）、`While` 语句、`do`-`while` 语句
	- 注释语句
单行注释（//）、多行注释（/*……*/）
- 系统提供的常用函数
	- 输入输出函数（对象方法） **` 掌握`**
`window`.`alert`() 消息对话框    `window`.`confirm`()  确认对话框
`window`.`prompt`()输入对话框   `document`.`write`()输出文本
注：由于`window` 是顶层对象，使用时可省。如：`window`.`alert`()可写成：`alert`() 
	- 字符串分析函数 **` 较高要求`**
`eval`(`str`)  计算字符串表达式值     `parseInt`(`str`, `radix`) 转换不同进制的数
`parseInt`(`str`) 将字符串转换为整数   `parseFloat`(`str`)将字符串转换为浮点数
- 用户自定义函数 **` 较高要求`**
- 基于面向对象的程序设计 **` 掌握`**
	- `JavaScript` 事件及事件处理属性
`click`，`dbclick`，`mouseover`，`mouseout`，`focus`，`blur`，`submit`，`reset`，`load`，`unload`
`on` 事件名 = 事件处理函数(或`JavaScript` 语句) 
	- 表单验证