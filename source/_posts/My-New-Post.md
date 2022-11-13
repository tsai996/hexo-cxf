---
title: vue介绍
date: 2022-11-13 17:09:21
top_img: ./images/vue.jpg
cover: ./images/vue.jpg
tags: 
 - vue
categories:
 - vue
---
## 什么是 Vue？
Vue (发音为 /vjuː/，类似 view) 是一款用于构建用户界面的 JavaScript 框架。它基于标准 HTML、CSS 和 JavaScript 构建，并提供了一套声明式的、组件化的编程模型，帮助你高效地开发用户界面。无论是简单还是复杂的界面，Vue 都可以胜任。

下面是一个最基本的示例：
```javascript
import { createApp } from 'vue'
createApp({
    data() {
        return {
            count: 0
        }
    }
}).mount('#app')
```
```html
<div id="app">
  <button @click="count++">
    Count is: {{ count }}
  </button>
</div>
```
上面的示例展示了 Vue 的两个核心功能：
- **声明式：** Vue 基于标准 HTML 拓展了一套模板语法，使得我们可以声明式地描述最终输出的 HTML 和 JavaScript 状态之间的关系。
- **响应性** Vue 会自动跟踪 JavaScript 状态并在其发生变化时响应式地更新 DOM。

你可能已经有了些疑问——先别急，在后续的文档中我们会详细介绍每一个细节。现在，请继续看下去，以确保你对 Vue 作为一个框架到底提供了什么有一个宏观的了解。
