# -Design-Patterns-Typescript

设计模式（以Typescript描述）

内容选自[此处](https://refactoringguru.cn/design-patterns/typescript)和[此处](https://github.com/fbeline/design-patterns-JS)，以及一定自己的理解。

## 分类

### 创建型模式

#### [工厂方法](docs/description/factory/index.md)

在父类中提供一个创建对象的接口， 允许子类决定实例化对象的类型。

#### [抽象工厂](docs/description/abstract-factory/index.md)

让你能创建一系列相关的对象， 而无需指定其具体类。


#### [原型](docs/description/prototype/index.md)

能够复制已有对象， 而又无需使代码依赖它们所属的类。


#### [生成器](docs/description/builder/index.md)

使你能够分步骤创建复杂对象。 该模式允许你使用相同的创建代码生成不同类型和形式的对象

#### [单例](docs/description/singleton/index.md)

保证一个类只有一个实例， 并提供一个访问该实例的全局节点。


### 结构型模式

#### [适配器](docs/description/adapter/index.md)

使接口不兼容的对象能够相互合作。


#### [桥接](docs/description/bridge/index.md)

可将一个大类或一系列紧密相关的类拆分为抽象和实现两个独立的层次结构， 从而能在开发时分别使用

#### [组合](docs/description/composite/index.md)

将对象组合成树状结构， 并且能像使用独立对象一样使用它们

#### [装饰器](docs/description/decorator/index.md)

将对象放入包含行为的特殊封装对象中来为原对象绑定新的行为

#### [外观（门面）](docs/description/facade/index.md)

为程序库、 框架或其他复杂类提供一个简单的接口


#### [享元](docs/description/flyweight/index.md)

摒弃了在每个对象中保存所有数据的方式， 通过共享多个对象所共有的相同状态， 让你能在有限的内存容量中载入更多对象。