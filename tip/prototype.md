## js 原型和原型

#### js原型与原型链之问

- js原型是什么鬼， 为什么还有原型链， 我只是想那它写写特效而已， 为什么要学它？

#### 如何从0开始， 通过最感性的方式认识原型链

结合当初我第一次接触原型链的经历， 通过纯粹理论化的途径学习它， 简直是是自寻烦恼，现在往网上有关原型链的好的教程大致有两个思路，一个是从下往上， 从最最简单的数据类型开始， 一步一步迭代构建原型以及原型链的概念， 逐步加深认知， 然后形成一个知识网络； 另一个思路是从上往下， 从语言创建哲学的角度来一步一步解释原型， 原型链到底是什么， 先宏观再微观！

两个角度都非常好， 那我就逐一介绍总结， 不过在总结之前， 需要先构建一个网络图， 通过图来解释更方便。

##### 图形



##### 从下到上的思路

- 1. js一切皆对象

数字是对象， 函数是对象， 布尔值是对象， 对象是对象， undefined是对象， null也是对象， 一切都是对象;

- 2. 所有对象都是由函数创建

- 3. 所有函数都是由函数创建

- 4. 所有函数都有一个原型， 且这个原型是一个对象

- 5. 由函数创建的对象都有一个隐士指针__proto__指向构造函数的原型， 进而链式指向

- 6. 有Object函数创建的对象的隐式原型的隐式原型为null(万物归空)

#### 原型链之图

#### 为什么需要原型链

#### 原型链主要用来干啥
