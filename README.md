# JAVA设计模式学习案例

## 一、设计模式六大原则
1.开闭原则

对扩展开放，对修改关闭

2.里氏代换原则

只有当衍生类可以替换掉基类，软件单位的功能不受到影响时，基类才能真正被复用，而衍生类也能够在基类的基础上增加新的行为 

3.依赖倒转原则

这个是开闭原则的基础，对接口编程，依赖于抽象而不依赖于具体

4.接口隔离原则

使用多个隔离的借口来降低耦合度

5.迪米特法则(最少知道原则)

一个实体应当尽量少的与其他实体之间发生相互作用，使得系统功能模块相对独立

6.合成复用原则

原则是尽量使用合成/聚合的方式，而不是使用继承。继承实际上破坏了类的封装性，超类的方法可能会被子类修改

## 二、设计模式分类
* 创建型模式：工厂方法模式，抽象工厂模式，单例模式，建造者模式，原型模式
* 结构型模式：适配器模式，装饰器模式，代理模式，外观模式，桥接模式，组合模式，享元模式
* 行为型模式：策略模式、模板方法模式、观察者模式、迭代子模式、责任链模式、命令模式、备忘录模式、状态模式、访问者模式、中介者模式、解释器模式

## 三、设计模式
1.单例模式（singleton）

定义：确保一个类只有一个实例，而且自行实例化并向整个系统提供这个实例

2.工厂方法模式（factory-method）

定义：定义一个用于创建对象的接口，让子类决定实例化哪一个类，工厂方法使一个类的实例化延迟到其子类

3.抽象工厂模式（abstract-factory）

定义：为创建一组相关或相互依赖的对象提供一个接口，而且无需指定他们的具体类

4.构造者模式（builder）

定义：将一个复杂对象的构建与它的表示分离，使得同样的构建过程可以创建不同的表示

5.原型模式（prototype）

定义：用原型实例指定创建对象的种类，并通过拷贝这些原型创建新的对象

6.适配器模式(adapter)

定义：将一个类的接口变换成客户端所期待的另一种接口，从而使原本因接口不匹配而无法在一起工作的两个类能够在一起工作

7.装饰器模式(decorator)

定义：动态地给一个对象添加一些额外的职责，装饰模式相比生成子类更为灵活

8.代理模式(proxy)

定义：为其他对象提供一种代理以控制对这个对象的访问

9.外观模式(facade)

定义：要求一个子系统的外部与其内部的通信必须通过一个统一的对象进行。外观模式提供一个高层次的接口，使得子系统更易于使用

10.桥梁模式(bridge)

定义：将抽象和实现解耦，使得两者可以独立地变化

11.组合模式(composite)

定义：将对象组合成树形结构以表示“部分-整体”的层次结构，使得用户对单个对象和组合对象的使用具有一致性

12.享元模式(flyweight)

定义：使用共享对象可有效地支持大量的细粒度的对象

13.策略模式(strategy)

定义：定义一组算法，将每个算法都封装起来，并且使他们之间可以互换

14.模板方法模式(template-method)

定义：定义一个操作中算法的框架，而将一些步骤延迟到子类中，使得子类可以不改变算法的结构即可重定义该算法中的某些特定步骤

15.观察者模式(observer)

定义：定义对象间一种一对多的依赖关系，使得每当一个对象改变状态，则所有依赖于它的对象都会得到通知并自动更新

16.迭代器模式(iterator)

定义：提供一种方法访问一个容器对象中各个元素，而又不暴露该对象的内部细节

17.责任链模式(responsibility-chain)

定义：使多个对象都有机会处理请求，从而避免了请求的发送者和接受者之间的耦合关系。将这些对象连成一条链，并沿着这条链传递该请求，知道有对象处理为止

18.命令模式(command)

定义：将一个请求封装成一个对象，从而让你使用不同的请求把客户端参数化，对请求排队或者记录请求日志，可以提供命令的撤销和恢复功能

19.备忘录模式(memento)

定义：在不破坏封装性的前提下，捕获一个对象的内部状态，并在该对象之外保存这个状态。这样就可以将该对象恢复到原先保存的状态

20.状态模式(state)

定义：允许一个对象在其内部状态改变时改变它的行为，对象看起来似乎修改了它的类

21.访问者模式(visitor)

定义：封装某些作用于某种数据结构中各元素的操作，它可以在不改变数据结构的前提下定义作用于这些元素的新的操作

22.中介者模式(mediator)

定义：用一个中介者对象封装一系列的对象交互，中介者使各对象不需要显示地相互作用，从而使耦合松散，而且可以独立地改变它们之间的交互

23.解释器模式(interpreter)

定义：给定一个语言，定义它的文法的一种表示，并定义一个解释器，这个解释器使用该表示来解释语言中的句子