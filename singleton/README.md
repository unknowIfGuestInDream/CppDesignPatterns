## 单例

确保一个类只有一个实例，并提供对它的全局访问点。
模式具有创建目的并处理对象关系，这些关系更多
动态。Singleton 通常用作另一种设计模式的一部分（参见 [Fa ade]
和[蝇量级]）。

### 何时使用

* 一个类必须只有一个实例，并且客户端必须能够从已知的访问点访问该实例
* 当唯一实例应该可以通过子类化进行扩展时，并且客户端应该能够在不修改其代码的情况下使用扩展实例
[Facade]: https://github.com/JakubVojvoda/design-patterns-cpp/tree/master/facade
[Flyweight]: https://github.com/JakubVojvoda/design-patterns-cpp/tree/master/flyweight
 
