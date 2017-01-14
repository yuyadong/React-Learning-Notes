# React-Learning-Notes
React 学习笔记

# 前端学习笔记

## 前言

写前端学习笔记是一份非常烧脑的任务，因为现今的前端开发已经到了一种近似疯狂的程度，读者无法通过一篇文章甚至书籍掌握所有知识点。

从大方面讲，自从Node.js、ECMAScript 6.0、TypeScript的兴起，前端已经完全脱离通过`<script>`标签引用一个组件的开发模式，相对应的是包管理(NPM)、打包发布(Webpack)等解决方案，而前端开发组件比如React、vue.js、Redux更多是开发思想上的转变，如果你还以jQuery+Bootstrap时代的思想来学习他们，结果是灾难性的。另外，前后端分离的思想也催生出工程化、RESTful、Mock、单元测试等一系列需要学习的新理念。

具体到细节，除了上文中提到知识点外，还涉及这些组件的大量插件库，也就是说会牵扯多达数十种组件和插件的使用。每个组件的特性、原理、底层逻辑都有差异，涵盖的知识面非常大。而难度最大的是怎么结合这些，打造一款符合自己产品的可迭代的前端架构。

> 参考 [《在 2016 年学 JavaScript 是一种什么样的体验？》](https://www.oschina.net/news/77853/how-about-learn-javascript-at-2016)

## 目的

写这篇笔记之前我经过很长时间的学习，也零散整理了一些笔记，它们的问题是知识点非常散且没有整体性和目的性。

- [React 学习笔记](https://github.com/maosong/React-Learning-notes)
- [ES6 学习不完全笔记](https://github.com/maosong/ES6-Learning-notes)
- [Gulp+Webpack 学习笔记](https://github.com/maosong/Gulp-Webpack-Learning-nodes)

这篇笔记的目的是结合实际项目，完整分层的阐述所涉及到的知识点，再配合其他更加优秀的文章（下文会提供链接）降低大家的学习成本。

## 知识点

简单来说会涉及Node.js、打包发布、前端框架、Mock、单元测试等知识点。

- Node.js部分主要介绍其安装和npm包管理方面的知识，相对简单。
- 打包发布通过Webpack及其第三方插件，按约定大于配置的理念简化打包流程。
- 前端框架我们的选型是React+Antd，并通过Redux进行状态管理，通过React-Router做前端路由，这也是最复杂的一部分。
- Mock保证前端开发不依赖后端API的开发进度。这里我们使用简单的mockjs,工程化开发推荐使用独立的Mock Server。
- 单元测试可选性产品很多，这里暂定Jest，结合Mock对action、reducers进行单元测试。

## 参考

### 官方文档

- [(MDN) Web 技术文档](https://developer.mozilla.org/zh-CN/docs/Web)
- [ECMAScript 6入门](http://es6.ruanyifeng.com/)
- [React 中文文档](http://wiki.jikexueyuan.com/project/react/)
- [Redux 中文文档](http://cn.redux.js.org/index.html)
- [(FSA约定) Flux Standard Action](https://github.com/acdlite/flux-standard-action)
- [Lodash Documentation](https://lodash.com/docs/)

### Webpack

- [Webpack 详解](http://www.cnblogs.com/sloong/p/5570774.html)
- [细说webpack之流程篇](http://www.cnblogs.com/yxy99/p/5852987.html)
- [如何十倍提高你的webpack构建效率](http://blog.csdn.net/u011413061/article/details/51872412)
- [webpack 代码拆分](https://segmentfault.com/a/1190000007649417)
- [多页为王：webpack多页应用架构专题系列](http://array_huang.coding.me/webpack-book/)

### React+Redux

- [React 入门实例教程](http://www.ruanyifeng.com/blog/2015/03/react.html)
- [一起理解 Virtual DOM](https://segmentfault.com/a/1190000007694388)
- [React+Redux系列教程](https://github.com/lewis617/react-redux-tutorial)
- [实例讲解基于 React+Redux 的前端开发流程](https://segmentfault.com/a/1190000005356568)
- [Redux 入门教程系列](http://www.ruanyifeng.com/blog/2016/09/redux_tutorial_part_one_basic_usages.html)
- [Redux状态管理方法与实例](http://www.cnblogs.com/luozhihao/p/5660496.html)
- [Redux 核心概念](http://www.jianshu.com/p/3334467e4b32)
- [Redux 官方TODO示例解析](https://zhuanlan.zhihu.com/p/22022941)
- [React 实践心得：react-redux 之 connect 方法详解](http://www.tuicool.com/articles/MrmYN36)
- [React创建组件的三种方式及其区别](http://www.cnblogs.com/wonyun/p/5930333.html)
- [初识React中的High Order Component](https://leozdgao.me/chushi-hoc/)
- [ReactJS修炼之路（二）：组件的key](http://blog.csdn.net/code_for_free/article/details/50514259)
- [react + redux性能优化之重复渲染](http://www.jianshu.com/p/b9b311f04707)
- [React + Redux 渲染性能优化原理](http://mt.sohu.com/20161003/n469574178.shtml)
- [Immutable 详解及 React 中实践](http://www.cnblogs.com/qiangxia/p/5522143.html)
- [译文《容器组件和展示组件》原作者：Dan Abramov](http://www.jianshu.com/p/6fa2b21f5df3)


### 实例

- [React 构建单页应用方法与实例](https://segmentfault.com/a/1190000005703694)
- [多项目共用基础设施](https://segmentfault.com/a/1190000007301770)


