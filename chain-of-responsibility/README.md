## 责任链

责任链模式避免将请求的发送方与其接收方耦合
通过为多个对象提供处理请求的机会。模式链
接收对象并沿链传递请求，直到对象处理它。
它具有行为目的并处理对象之间的关系。

### 何时使用

* 一个请求可以处理多个对象，并且应自动确定处理程序
* 您希望向多个对象之一发出请求，而不显式指定接收方
* 可以处理请求的对象集应动态指定