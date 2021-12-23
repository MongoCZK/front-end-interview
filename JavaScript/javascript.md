#### 🕛 0.1+0.2 === 0.3 吗？为什么 [参考链接](https://www.javascriptc.com/books/nodejs-roadmap/javascript/floating-point-number-0.1-0.2.html)

#### 📗 JS 数据类型

- 基本类型： Number、Boolean、String、Null、Undefined、Symbol（ES6）、BigInt（ES2020）
- 引用类型： Object、对象子类型（Array、Function）

#### 📗 JS 整数是怎么表示的

通过Number类型来表示，遵循IEEE754标准，通过64位来表示一个数字（1+11+52），最大安全数字是Math.pow(2,53)-1，对于16为十进制，符号位 + 指数位 + 小数部分有效位

#### 📗 Number()的存储空间是多大？如果后台发送了一个超过最大值得数字怎么办？

存储空间为Math.pow(2,53)，53为有效数字，会发生截断，等于JS能支持的最大数字

#### 🕛 事件流

[参考链接](https://juejin.im/entry/5826ba9d0ce4630056f85e07)

#### 事件是如何实现的

基于发布订阅模式，就是在浏览器加载的时候会读取事件相关的代码，但是只有实际等到具体的事件触发的时候才会执行

在Web端，常见的就是DOM事件：
+ DOM0级事件， 直接在html元素上绑定on-event，比如onclick；取消事件使用 dom.onclick = null， 同一个事件只能有一个处理程序，后面的会覆盖前面的

+ DOM2级事件， 通过addEventListener注册事件，通过removeEventListener来删除事件，一个事件可以有多个时间处理程序，按顺序执行，捕获时间和冒泡事件
+ DOM

6. 🕛 事件是如何实现的
7. 🕛 new 一个函数的时候发生了什么
8. 🕛 new 一个构造函数，如果函数返回 return {}, return null, return 1, return true 会发生什么
9. 🕛 Symbol 有什么用处
10. 🕛 闭包是什么
11. 🕛 NaN 是什么，用 typeof 会输出什么
12. 🕛 this 指向，bind，call，apply 具体指什么
13. 🕛 setTimeout(fn, 0)多久才执行， event loop
14. 🕛 js 脚本加载问题，async，defer 问题
15. 🕛 如何判断一个对象是不是空对象
16. 🕛 原型链和原型链继承
17. 🕛 数组能够调用的函数有哪些
18. 🕛 如何判断数组、对象
19. 🕛 函数中的 arguments 是数组吗？ 类数组转数组的方法？
20. 🕛 TypeScript 的作用是什么
21. 🕛 对 JS 的了解
22. 🕛 ES6 之前使用 prototype 实现继承
23. 🕛 如果一个构造函数，bind 了一个对象，用这个构造函数创建出的实例会继承这个对象的属性吗？ 为什么？
24. 🕛 箭头函数和普通函数有啥区别？ 箭头函数能当构造函数吗？
25. 🕛 ES6 的 class 和 static
26. 🕛 事件循环机制（Event Loop）
27. 🕛 let 闭包
28. 🕛 变量提升
