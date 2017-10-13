# Damo中文文档

---

Damo是一套完整前端开发框架，通过JSX和JavaScript编译成JavaScript的语言，来构建客户端应用。

Damo框架包括前端应用开发所用到的一系列库，有些是核心库，有些是可选库。核心库引导你开发的各代码模块串通起来，使得应用可以正常启动和访问；可选库帮助你解决特定的业务逻辑问题或者编写更灵活的前端代码。

### Damo的特性与优点

#### 数据驱动

1. 可预测的状态容器

  Damo会把应用拆分成多个独立视图和视图渲染需要的状态数据（理解[概念](#概念)），应用的所有状态数据通过机制存储到单一的状态容器，这种机制就是使用响应式虚拟依赖状态图表，可以直观的理解和遇到应用每个视图的不同时刻的状态数据结构。

2. 状态驱动视图渲染

  视图需要渲染为特定状态，借助于Damo数据驱动模型，在状态容器中选定状态数据后，和视图建立连接成功后，从而驱动视图和状态数据进行渲染。


#### 生产效率

1. 模板即组件

  搭配组件框架[React](http://www.runoob.com/react/react-tutorial.html)，一切模板都属于组件，模板结构以JSX语法进行开发（类HTML语法，所有HTML都属于JSX）。所以模板即组件，组件即HTML自定义标签，组件是包含了模板代码的一种特殊的HTML标签类型。

2. Damo CLI

  Damo提供了命令行工具，快速进入开发、调试和投建环节，最终部署整个应用。


#### 速度与性能

1. 代码拆分

  借助[React-Router](http://react-guide.github.io/react-router-cn/docs/API.html)路由器以及CLI命令行工具，Damo可以实现快速加载。自动代码拆分机制可以让用户仅仅加载哪些用于渲染所请求页面的代码。

2. 安全与统一

  借助React的安全机制，解决应用构建遇到的安全问题。

  JavaScript虚拟机进行高度优化，轻松获得框架提供的高生产率，同时又能保留所有手写代码的优点。


#### 完整的开发故事

1. 整站解决方案

  Damo是应用开发的整套方案，包括目录结构、代码组织、组件开发、服务开发、状态管理等视图展示，同时提供实用的应用的特定模块的解决方案以及前后端开发模式的编程思路。

2. 前端先行

  借助于CLI和数据模拟套件，帮助你提前构建前端应用，无需等待数据接口就绪。在后续数据接口具备后，无缝切换到真实数据接口。


### 开发原则

1. 服务是通过JS完成一件特定的事情，对象、函数、类都可以是一个服务。

2. 单一应用状态容器，状态的使用通过服务来应用。

3. 视图只分为组件和服务，其本质都是JS类。

4. 元数据是用来描述应用中JS类如何工作。


### 概念

1. 状态

2. 状态容器

3. 组件

4. 模板

5. 服务

6. 视图

7. 元数据

8. 装饰器


