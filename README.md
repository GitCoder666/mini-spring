# <img src="assets/spring-framework.png" width="80" height="80"> mini-spring
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen)](https://github.com/DerekYRC/mini-spring)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

## 关于
**mini-spring**是简化版的spring框架，能帮助你快速熟悉spring源码和掌握spring的核心原理。抽取了spring的核心逻辑，代码极度简化，保留spring的核心功能，如IoC和AOP、资源加载器、事件监听器、类型转换、容器扩展点、bean生命周期和作用域、应用上下文等核心功能。

如果本项目能帮助到你，请给个**STAR，谢谢！！！**

## 功能
#### 基础篇
* [IoC]()
    * [实现一个简单的容器](#)
    * [BeanDefinition和BeanDefinitionRegistry]()
    * [Bean实例化策略InstantiationStrategy]()
    * [为bean填充属性]()
    * [为bean注入bean]()
    * [资源和资源加载器]()
    * [在xml文件中定义bean]()
    * [容器扩展机制BeanFactoryPostProcess和BeanPostProcessor]()
    * [应用上下文ApplicationContext]()
    * [bean的初始化和销毁方法]()
    * [Aware接口]()
    * [FactoryBean]()
    * [类型转换]()
    * [容器事件和事件监听器]()
* [AOP]()
    * [JDK动态代理]()
    * [CGLib动态代理]()
    * [织入方法判断]()
    * [动态代理融入bean生命周期]()


#### 扩展篇
* [bean作用域，增加prototype的支持]()
* [PropertyPlaceholderConfigurer]()
* [包扫描]()
* [基于注解的依赖注入Autowired]()

#### 高级篇
* [解决循环依赖问题]()

## 使用方法
每个功能点对应一个分支，切换到功能点对应的分支了解新增的功能，增量改动点在[changelog.md](https://github.com/DerekYRC/mini-spring/blob/main/changelog.md)文件中描述。

## 参考
- [《Spring源码深度解析》](https://book.douban.com/subject/25866350/)
- [《精通Spring 4.x》](https://book.douban.com/subject/26952826/)
- [tiny-spring](https://github.com/code4craft/tiny-spring)
