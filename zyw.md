### webpack
Webpack有哪些可以配置的参数
loader和plugin的区别
loader执行顺序？
### ts
枚举有哪些特点、编译之后区别
Ts实现继承的方式
class的public和protected、private区别
interface和type有什么区别
说一下泛型概念以及使用场景
### react
Hooks引入的意义
usecallback用法
useRef和useState有什么区别
Filber做了什么优化更新
dom的diff算法
现在的dom结构和之前15的有什么区别
Context的用法，优缺点,和redux相比技术选型如何考虑？
共用组件有哪些方式
React.memo的优点
### 设计相关
函数式编程是什么，有什么特点，比起其他的面向对象编程有什么优势
用过哪些设计模式，最喜欢的是哪个？比起其他有什么优势？
### js
es5实现class继承
原型链与继承有哪些方式
异步（比如promise）的引入解决了什么问题
事件循环写结果，具体忘了
实现instanced
this指向：
```javascript
function Foo() {
    Foo.a = function() {
        console.log(1)
    }
    this.a = function() {
        console.log(2)
    }
}
Foo.prototype.a = function() {
    console.log(3)
}
Foo.a = function() {
    console.log(4)
}
Foo.a();
let obj = new Foo(); 
obj.a();
Foo.a();
```
es5实现promise.all
es5实现class继承
es5实现promise

### 编程题
1. 栈
    给定一个只包括 '('，')'，'{'，'}'，'['，']' 的字符串 s ，判断字符串是否有效。
    有效字符串需满足：
    ● 左括号必须用相同类型的右括号闭合。
    ● 左括号必须以正确的顺序闭合。
    示例：checkBrackets('[(])') => false; checkBrackets('[()]') => true; 
2. 环
    如何判断单向链表有环？

