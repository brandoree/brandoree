**面试官**：**来说说你对restful的理解？**  

大彬：REST，英文全称，Resource Representational State Transfer，对资源的访问状态的变化通过url的变化表述出来  

大彬：Resource：**资源**。资源是REST架构或者说整个网络处理的核心

大彬：Representational：**某种表现形式**，比如用JSON，XML，JPEG等

大彬：State Transfer：**状态变化**。通过HTTP method实现

大彬：REST描述的是在网络中client和server的一种交互形式

大彬：用大白话来说，就是**通过URL就知道要什么资源，通过HTTP method就知道要干什么，通过HTTP status code就知道结果如何**

大彬：举个例子

`GET /tasks 获取所有任务   POST /tasks 创建新任务   GET /tasks/{id} 通过任务id获取任务   PUT /tasks/{id} 更新任务   DELETE /tasks/{id} 删除任务   `

大彬：GET代表获取一个资源，POST代表添加一个资源，PUT代表修改一个资源，DELETE代表删除一个资源。

大彬：server提供的RESTful API中，URL中只使用名词来指定资源，原则上不使用动词。

大彬：用`HTTP Status Code`传递server的状态信息。比如最常用的 200 表示成功，500 表示Server内部错误等。

旁白：总结一下，就是用URL定位资源，用HTTP描述操作

**面试官**：**嗯，那你觉得使用Restful风格有什么优势呢？**

大彬：第一，**风格统一**，不会出现`delUser/deleteUser/removeUser`各种命名的代码了

大彬：第二，**面向资源**，一目了然，具有自解释性

大彬：第三，**充分利用 HTTP 协议本身语义**

旁白：好吧，其他的编不下去了...

**面试官**：不错，今天面试就到这吧