# 前提
* 公司项目，一个简化的antd-react通用模板放上来 


# react-antd-webpack 通用
* 登录页面login
* 侧边栏：上面是一个logo，下面是可展开的各级菜单。点击菜单项时，右边会展示相应的内容。
* Header：展示当前登录的用户名和面包屑导航，还可能有自定义的一些菜单之类
* 内容区：展示具体的内容，跟业务有关的
* Footer：展示copyright之类的
* 还有些看不到的，比如登录、注销等


## Quick Start

在自己的机器上调试：

1. 保证node版本5.3+，npm版本3.3+
2. clone下来后，`npm install`，安装必要的依赖
3. `npm run dev`，启动webpack-dev-server，打开浏览器`http://localhost:8080`查看效果。
4. 要用模拟数据可以使用mock(mockjs.com)

## 技术栈

- react@15.3.1
- react-router@15.3.1
- redux@3.6.0
- webpack@1.14.2
- es6
- antd (https://ant.design)


## 一些说明

### 安全/权限问题

目前对安全&权限都没考虑进去，如果有这方面的要求，只能后端校验了。在请求后端接口时校验用户的身份和权限。

权限问题也很麻烦，感觉不太好做成通用的东西，如果有需求的话，还是自己定制开发比较好。

### 浏览器兼容性

能力所限，只能保证chrome等高级浏览器中正常使用...

