# java设计模式学习案例

1.单例模式（singleton）

定义：确保一个类只有一个实例，而且自行实例化并向整个系统提供这个实例。

2.工厂方法模式（factory-method）

定义：定义一个用于创建对象的接口，让子类决定实例化哪一个类，工厂方法使一个类的实例化延迟到其子类。

3.抽象工厂模式（abstract-factory）

定义：为创建一组相关或相互依赖的对象提供一个接口，而且无需指定他们的具体类

4.构造者模式（builder）

定义：将一个复杂对象的构建与它的表示分离，使得同样的构建过程可以创建不同的表示

5.原型模式（prototype）

定义：用原型实例指定创建对象的种类，并通过拷贝这些原型创建新的对象

6.模板方法模式（template-method）

定义：定义一个操作中算法的框架，而将一些步骤延迟到子类中，使得子类可以不改变算法的结构即可重定义该算法中的某些特定步骤

7.中介者模式（mediator）

定义：用一个中介者对象封装一系列的对象交互，中介者使各对象不需要显示地相互作用，从而使耦合松散，而且可以独立地改变它们之间的交互

8.观察者模式（observer）

定义：定义对象间一种一对多的依赖关系，使得当每一个对象改变状态，则所有依赖于它的对象都会得到通知并自动更新

9.访问者模式（visitor）

定义：封装某些作用于某种数据结构中各元素的操作，它可以在不改变数据结构的前提下定义作用于这些元素的新的操作

10.命令模式（command）

定义：将一个请求封装成一个对象，从而让你使用不同的请求把客户端参数化，对请求排队或者记录请求日志，可以提供命令的撤销和恢复功能