## 蝇量级

蝇量级模式具有结构目的，适用于对象并使用共享来支持
高效处理大量细粒度对象。该模式可用于减少
需要创建大量相似对象时的内存使用情况。

### 何时使用

* 当一个类的一个实例可用于提供多个“虚拟实例”时
* 当以下所有情况均为真时
 * 应用程序使用大量对象
 * 由于物品数量庞大，存储成本很高
 * 大多数对象状态都可以是外在的
 * 一旦外部状态被删除，许多对象组可能会被相对较少的共享对象所取代
 * 应用程序不依赖于对象标识