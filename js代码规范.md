# js代码规范

### 地址：https://www.jianshu.com/p/d60116a0e6c0

1.  使用一个tab 作为缩进层级

2. 每条语句以；结尾

3. 一行代码长度在80字符以内，单行代码达到最大限度时候拆分成两行，下一行增加两个缩进层级

4. 添加空行：

   - 方法之间
   - 局部变量与第一条语句之间
   - 单行多行注释之前
   - 方法逻辑片段之间

5. 命名：

   命名长度要尽可能短，并抓住要点。

   - 变量命名：前缀名词
   - 函数命名： 前缀是动词，has，is，set，get。。。
   - 常量命名： 使用大写字母和下划线构成

6. 使用if或者for语句，不论单行还是多行代码都要使用花括号

7. switch 不要连续执行case（要加入‘break；’），即使什么都不做也不要省略default。

8. 尽量不使用continue，用if语句代替continue功能

9. for-in循环是用来遍历对象属性的，但它还遍历原型继承的属性，最好使用hasOwnProrerty()（判断是否是自身属性（非继承））过滤实例属性

10. 推荐函数顶部使用var语句声明接下来可能用到的变量，没有初始值的变量应该出现在var语句尾部。

11. 将css从JavaScript 中分离，JavaScript修改样式元素，最佳方法是操作css的className

12. 将JavaScript从html抽离，可以使用addListener()添加行为。

13. typeof 检测原始值，instanceof检测引用值

14. 检测某个属性是否存在 in/hasOwnProperty



###  注释规范： https://www.jianshu.com/p/822aa0077595

