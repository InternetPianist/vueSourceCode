数据驱动

# Vue与模板

使用步骤:

1. 编写 页面 模板 
   1. 直接在 HTML 标签中写 标签
   2. 使用 template
   3. 使用 单文件 ( <template /> )
2. 创建 Vue 的实例
   1. 在 Vue 的构造函数中提供: data, methods, computed, watcher, props, ...
3. 将 Vue 挂载到 页面中 ( mount )

# 数据驱动模型

Vue 的执行流程
1. 获得模板：模板中有“字符串变量”
2. 利用Vue 构造函数中所提供的数据来“字符串变量”，得到可以在页面中显示的标签
3. 根据字符串变量替换数据

Vue 利用 我们提供的数据 和 页面中 模板 生成了 一个新的 HTML 标签 ( node 元素 ),
替换到了 页面中 放置模板的位置.

如何实现

# 简单的模板渲染

# 虚拟DOM

目标：

1. 怎么将真正的 DOM 转换为 虚拟 DOM
2. 怎么将虚拟 DOM 转换为 真正的 DOM

深拷贝类似
