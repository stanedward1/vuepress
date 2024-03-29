<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
**Table of Contents**  *generated with [DocToc](https://github.com/thlorenz/doctoc)*

- [类与实例](#%E7%B1%BB%E4%B8%8E%E5%AE%9E%E4%BE%8B)
- [构造方法](#%E6%9E%84%E9%80%A0%E6%96%B9%E6%B3%95)
- [方法重载](#%E6%96%B9%E6%B3%95%E9%87%8D%E8%BD%BD)
- [封装，继承，多态](#%E5%B0%81%E8%A3%85%E7%BB%A7%E6%89%BF%E5%A4%9A%E6%80%81)
  - [封装](#%E5%B0%81%E8%A3%85)
  - [继承](#%E7%BB%A7%E6%89%BF)
  - [多态](#%E5%A4%9A%E6%80%81)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

**我们谈到面向对象的时候，免不了会说到对象和类，偶尔看到一个很有意思的说法：*对象可以类比我喜欢某人，而类则是我喜欢某类人***

# 类与实例

**一切事物皆对象——对象是一个自包含的实体，用一组可识别的特性和行为来标识**

OOP即针对对象来进行编程。

类：一大群人看电影应该在电影院，而不是家里的沙发上。类就是具有相同的功能的对象的抽象的集合。

实例：一大群人看电影应该是去电影院，那么去哪个电影院也是一个很重要的问题，实例，就是一个真实的对象。实例化就是创建对象的过程，一般使用new关键字来创建。

# 构造方法

构造方法，也叫构造函数，作用是对类进行初始化。

# 方法重载

方法重载提供了创建同名的多个方法的能力，但这些方法需使用不同的参数类型。

构造方法可以重载，普通方法也是可以重载的。

**方法重载可以在不改变原方法的基础上，新增功能。**

# 封装，继承，多态

## 封装

1. **良好的封装可以减少耦合**
2. **类内部的实现可以自由的修改**
3. **类具有清晰的对外接口**

<u>把会变化的部分取出来并“封装”起来，好让其他部分不会受到影响——代码变化引起的不经意后果变少，系统变得更有弹性。</u>

## 继承

**定义父类和子类——子类继承父类所有的特性，还可以定义新的特性**

**如果子类继承于父类**

<u>第一、子类拥有父类非private的属性和功能</u>

<u>第二、子类具有自己的属性和功能，即子类可以扩展父类没有的属性和功能</u>

<u>第三、子类还可以以自己的方式实现父类的功能（方法重写）。</u>

**继承的缺点：父类变，子类也变--------继承是一种类与类之间强耦合的关系。**

## 多态

**多态表示不同的对象可以执行相同的动作，但是要通过它们自己的实现代码来执行。**

![img](assets/java-polymorphism-111.png)

(图片来自菜鸟教程)
