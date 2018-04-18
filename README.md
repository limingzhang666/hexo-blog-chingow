# learn-markdown
### Samrt框架介绍
框架的意义在于减少重复编码，统一格式，提供必要的公共功能。


在使用Spring 配合 MyBatis 、通用Mapper插件、PageHelper分页插件 连做了几个中小型API项目，做下来觉得这套框架、工具搭配起来开发这种项目确实非常舒服，团队的反响也不错。在项目搭建和开发的过程中也总结了一些小经验，与大家分享一下。

在开发一个API项目之前，搭建项目、引入依赖、配置框架这些基础活自然不用多说，通常为了加快项目的开发进度（早点回家）还需要封装一些常用的类和工具，比如统一的响应结果封装、统一的异常处理、接口签名认证、基础的增删改差方法封装、基础代码生成工具等等，有了这些项目才能开工。

然而，下次再做类似的项目上述那些步骤可能还要搞一遍，虽然通常是拿过来改改，但是还是比较浪费时间。所以，可以利用面向对象抽象、封装的思想，抽取这类项目的共同之处封装成了一个种子项目（估计大部分公司都会有很多类似的种子项目），这样的话下次再开发类似的项目直接在该种子项目上迭代就可以了，减少无意义的重复工作。

## 主要包括以下模块
- [ ] smart-dependencies
- [ ] smart-core
- [ ] smart-support
- [ ] smart-rest
- [ ] smart-web

