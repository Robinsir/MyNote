# Vue Router 起步

起步
1. router-link 用来组件导航，to 属性指定链接（默认被渲染成a标签）
2. router-view 路由出口，匹配到组件将被渲染到router-view
3. 构建routes，传入 path，component，构建VueRouter实例,注意整个.VUE就是一个组件 ，通过**export defualt**来实现组件**参数构建**
4. 挂载router(别忘记)
5. ？export default 为什么导出就是一个组件： vue文件特性，利用export default 传入构建参数，实际上是一个局部组件
