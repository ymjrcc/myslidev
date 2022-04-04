---
# try also 'default' to start simple
theme: seriph
title: "程序员如何拥有一个 Side Project？"
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: "/img/bg.jpg"
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: true
colorSchema: 'dark'
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
---

<div class="text-5xl text-gray-200 mb-6">程序员如何拥有一个</div>
<div class="text-5xl text-gray-200 mb-12">Side Project？</div>

<div class="text-2xl text-blue-300">

——以  “[我的人人](http://localhost:3000/)”  为例

</div>

<div class="pt-20 text-gray-300 text-right">研发中心-工程二组 (火星)</div>
<div class="pt-4 text-gray-300 text-right pr-18">何一鸣</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
layout: image
image: "/img/bg1.jpg"
---

<div class="flex mb-6">
  <div class="w-145 mr-6 rounded-lg p-4 bg-gray-50 bg-opacity-20">
    <div v-click class="text-2xl title font-bold mb-2">什么是 Side Project</div>
    <ul>
      <li v-click class="leading-6 text-sm text-gray-200">人们将各种业余时间打造的产品或项目称为 “Side Project”。</li>
      <li v-click class="leading-6 text-sm text-gray-200">Side Project 的初始需求，往往来源于自己或身边人，最开始只要满足自己或者最小群体的需求就足够了。</li>
      <li v-click class="leading-6 text-sm text-gray-200">MVP(Minimum Viable Product)，最小可用产品，从产品的核心功能开始构建。</li>
      <li v-click class="leading-6 text-sm text-gray-200">一个 Side Project，无论最终能否给你带来回报，把自己的想法从 0 到 1 实现，本身就是一个快乐而充实的过程。</li>
    </ul>
  </div>
  <div class="flex-1 rounded-lg p-4 bg-gray-50 bg-opacity-20">
    <div v-click class="text-2xl title font-bold mb-2">Side Project 的意义</div>
    <ul class="text-sm text-gray-200">
      <li v-click>解决自己或别人的问题</li>
      <li v-click>练手，提高技术</li>
      <li v-click>赚钱</li>
      <li v-click>Just For Fun</li>
      <li v-click>……</li>
    </ul>
  </div>
</div>
<div class="rounded-lg p-4 bg-gray-50 bg-opacity-20 h-55">
<div v-click class="text-2xl title font-bold mb-2">举几个栗子</div>
<v-clicks>

- Vue
- [简书](https://www.jianshu.com/)
- [雪球神器](https://github.com/ymjrcc/xueqiu_crx)
- [metro](https://ymjrcc.github.io/metro/)

</v-clicks>
</div>

<style>
.title {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image
image: "/img/bg2.jpg"
---

<v-click>

# 开始前问自己几个问题：

</v-click>

<br/>

<div class="rounded-lg p-6 bg-gray-50 bg-opacity-20">
<v-clicks>

- ❓ **What** - 我的产品是什么?（要做什么，不做什么，产品需求边界）
- ❓ **Why** - 我为什么要做它？（99%的需求都已经有人实现过，只有多想一步，才能创造价值）
- ❓ **How** - 我打算如何实现它？（用什么技术，预计花多长时间，做到什么程度）

</v-clicks>
</div>

<br/>
<br/>

<h1 v-click>我工作太忙，没有时间做怎么办？</h1>
<br/>
<div class="rounded-lg p-6 bg-gray-50 bg-opacity-20">
  <h2 v-click class="text-green-500 italic mb-4">不，你有！</h2>
  <div class="text-gray-300 text-sm italic" v-click>✅ 需求驱动 ✅ 兴趣驱动 ✅ 善用零碎时间</div>
</div>

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  padding-bottom: 5px;
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>


---
layout: image
image: "/img/bg3.jpg"
---

# 需求清单和项目里程碑

<div class="rounded-lg p-3 bg-gray-50 bg-opacity-20">
  <div>
    <span class="text-blue-300">分类拆解：</span>
    <span v-click class="text-base">将整个工程分门别类，然后细化成一个个小任务，巧用 TODO，做一个勾一个</span>
  </div>
  <div>
    <span class="text-blue-300">需求迭代：</span>
    <span v-click class="text-base">做好规划，想好再改</span>
  </div>
</div>

<br/>
<div class="flex justify-around">
  <img v-click src="/img/01.png" class="h-85"/>
  <img v-click src="/img/02.png" class="h-85"/>
  <img v-click src="/img/03.png" class="h-85"/>
</div>

<style>
h1 {
  padding-bottom: 5px;
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image
image: "/img/bg8.jpg"
---
# 版本迭代：产品是如何演变的

<div class="rounded-lg p-6 bg-gray-500 bg-opacity-50 mt-6 text-blue-300">

- v0.0.0: <span v-click class="pl-2 text-white">有个需求——人人网要倒闭了，我要把我的发的状态都存下来</span>
- v0.0.1: <span v-click class="pl-2 text-white">实现方式——用笔记软件存太麻烦了，写个网页存下来吧</span>
- v0.1.0: <span v-click class="pl-2 text-white">加功能——有的状态带图片，图片存在相册里，那也要把相册存下来（路由）</span>
- v0.1.1: <span v-click class="pl-2 text-white">加功能——相册都有了，日志没有说不过去吧</span>
- v0.1.2: <span v-click class="pl-2 text-white">加功能——好友也是回忆的一部分，把好友信息也存下来</span>
- v0.2.0: <span v-click class="pl-2 text-white">页面这么多了，用状态页做首页不合适，再写个首页做总览</span>
- v0.2.1: <span v-click class="pl-2 text-white">重要的事件分散在各个页面里，按时间顺序捋出来，做个时间轴</span>
- v0.3.0: <span v-click class="pl-2 text-white">既然有了很多数据，做个可视化数据分析</span>
- v0.4.0: <span v-click class="pl-2 text-white">需求做完了，用户体验和性能优化</span>

</div>

<style>
h1 {
  padding-bottom: 5px;
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image
image: "/img/bg8.jpg"
---

# 产品结构

<img v-click src="/img/mind.png" />

<style>
h1 {
  padding-bottom: 5px;
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image
image: "/img/bg4.jpg"
---
# Coding 准备

<div class="rounded-lg p-3 bg-gray-50 bg-opacity-20 mt-6 w-120">
<div v-click class="text-xl text-blue-300 mb-2">工欲善其事，必先利其器：准备合适的工具</div>
<div class="ml-6">
<v-clicks>

- 代码托管：GitHub Private Repository
- 编辑器：VS Code + 项目管理器插件
- 需求与进度管理、笔记记录：Logseq
- ……

</v-clicks>
</div>
</div>

<div class="rounded-lg p-3 bg-gray-50 bg-opacity-20 mt-6 w-120">
<div v-click class="text-xl text-blue-300 mb-2">怎么舒服怎么来：选择最适合自己的技术栈</div>
<div class="ml-6">
<v-clicks>

- React （create-react-app）
- Ant Design
- echarts
- ……

</v-clicks>
</div>
</div>

<div class="absolute right-14 top-27 rounded-lg p-3 bg-gray-50 bg-opacity-20 w-90 h-100">
1111
</div>


<style>
h1 {
  padding-bottom: 5px;
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image
image: "/img/bg5.jpg"
---
# Coding 原则

<div class="rounded-lg p-3 bg-gray-50 bg-opacity-20 mt-4 w-120">
<div v-click class="text-xl text-blue-300 mb-2">不怕折腾，放心大胆地尝试最新技术</div>
<div class="ml-6">
<v-clicks>

- TailWind CSS → Windi CSS
- React 17 → React 18

</v-clicks>
</div>
</div>

<div class="rounded-lg p-3 bg-gray-50 bg-opacity-20 mt-4 w-120">
<div v-click class="text-xl text-blue-300 mb-2">使用工具，强行约束</div>
<div class="ml-6">
<v-clicks>

- [React.StrictMode](https://zhuanlan.zhihu.com/p/401329405)
- TypeScript + ts-standard

</v-clicks>
</div>
</div>

<div class="rounded-lg p-3 bg-gray-50 bg-opacity-20 mt-4 w-120">
<div v-click class="text-xl text-blue-300 mb-2">追求代码质量，拒绝天马行空</div>
<div class="ml-6">
<v-clicks>

- DRY：函数复用、组件模块抽取
- 代码优化、重构
- 逻辑与数据解耦

</v-clicks>
</div>
</div>

<div class="absolute right-14 top-25 rounded-lg p-3 bg-gray-50 bg-opacity-20 w-92 h-109">
1111
</div>


<style>
h1 {
  padding-bottom: 5px;
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image
image: "/img/bg6.jpg"
---
# Coding 心得

<div class="rounded-lg px-3 py-2 bg-gray-50 bg-opacity-20 mt-4 w-120">
<div v-click class="text-xl text-blue-300 mb-1">笔记与代码同行，做好知识沉淀</div>
<div class="ml-6">
<v-clicks>

- 代码片段（简陋版 dayjs）
- 工具技巧（VS Code 正则搜索替换）

</v-clicks>
</div>
</div>

<div class="rounded-lg px-3 py-2 bg-gray-50 bg-opacity-20 mt-4 w-120">
<div v-click class="text-xl text-blue-300 mb-1">善用但克制使用第三方库</div>
<div class="ml-6">
<v-clicks>

- 杜绝层层封装（echarts-for-react）
- 不要为了一个小功能引入一个大依赖（dayjs）
- 能自己实现就自己实现（[瀑布流](https://github.dev/ymjrcc/myrenren)）

</v-clicks>
</div>
</div>

<div class="rounded-lg px-3 py-2 bg-gray-50 bg-opacity-20 mt-4 w-120">
<div v-click class="text-xl text-blue-300 mb-1">拥抱社区和开源</div>
<div class="ml-6">
<v-clicks>

- 用社群 / issue 提问，反馈 bug 和问题（[如何提问](https://www.yuque.com/docs/share/aedf72a6-e5e5-4bf4-b95f-12c19dddffdd)）
- 发现 bug 若有能力自行修复，可提 pr 反哺社区
- 考虑开源自己的作品

</v-clicks>
</div>
</div>

<div class="absolute right-14 top-25 rounded-lg p-3 bg-gray-50 bg-opacity-20 w-92 h-108">
1111
</div>


<style>
h1 {
  padding-bottom: 5px;
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---
layout: image
image: "/img/bg7.jpg"
---

# Coding

Use code snippets and get the highlighting directly![^1]
<div class="flex">
<div class="flex-1">
asdfasdfasdfasdfasfasd
</div>
<div class="flex-1">

```ts {all|2|1-6|9|all}
interface User {
  id: number
  firstName: string
  lastName: string
  role: string
}

function updateUser(id: number, update: User) {
  const user = getUser(id)
  const newUser = { ...user, ...update }
  saveUser(id, newUser)
}
```

</div>
</div>

<style>
h1 {
  padding-bottom: 5px;
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# Components

<div grid="~ cols-2 gap-4">
<div>

You can use Vue components directly inside your slides.

We have provided a few built-in components like `<Tweet/>` and `<Youtube/>` that you can use directly. And adding your custom components is also super easy.

```html
<Counter :count="10" />
```

<!-- ./components/Counter.vue -->
<Counter :count="10" m="t-4" />

Check out [the guides](https://sli.dev/builtin/components.html) for more.

</div>
<div>

```html
<Tweet id="1390115482657726468" />
```

<Tweet id="1390115482657726468" scale="0.65" />

</div>
</div>


---
class: px-20
---

# Themes

Slidev comes with powerful theming support. Themes can provide styles, layouts, components, or even configurations for tools. Switching between themes by just **one edit** in your frontmatter:

<div grid="~ cols-2 gap-2" m="-t-2">

```yaml
---
theme: default
---
```

```yaml
---
theme: seriph
---
```

<img border="rounded" src="https://github.com/slidevjs/themes/blob/main/screenshots/theme-default/01.png?raw=true">

<img border="rounded" src="https://github.com/slidevjs/themes/blob/main/screenshots/theme-seriph/01.png?raw=true">

</div>

Read more about [How to use a theme](https://sli.dev/themes/use.html) and
check out the [Awesome Themes Gallery](https://sli.dev/themes/gallery.html).

---
preload: false
---

# Animations

Animations are powered by [@vueuse/motion](https://motion.vueuse.org/).

```html
<div
  v-motion
  :initial="{ x: -80 }"
  :enter="{ x: 0 }">
  Slidev
</div>
```

<div class="w-60 relative mt-6">
  <div class="relative w-40 h-40">
    <img
      v-motion
      :initial="{ x: 800, y: -100, scale: 1.5, rotate: -50 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-square.png"
    />
    <img
      v-motion
      :initial="{ y: 500, x: -100, scale: 2 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-circle.png"
    />
    <img
      v-motion
      :initial="{ x: 600, y: 400, scale: 2, rotate: 100 }"
      :enter="final"
      class="absolute top-0 left-0 right-0 bottom-0"
      src="https://sli.dev/logo-triangle.png"
    />
  </div>

  <div
    class="text-5xl absolute top-14 left-40 text-[#2B90B6] -z-1"
    v-motion
    :initial="{ x: -80, opacity: 0}"
    :enter="{ x: 0, opacity: 1, transition: { delay: 2000, duration: 1000 } }">
    Slidev
  </div>
</div>

<!-- vue script setup scripts can be directly used in markdown, and will only affects current page -->
<script setup lang="ts">
const final = {
  x: 0,
  y: 0,
  rotate: 0,
  scale: 1,
  transition: {
    type: 'spring',
    damping: 10,
    stiffness: 20,
    mass: 2
  }
}
</script>

<div
  v-motion
  :initial="{ x:35, y: 40, opacity: 0}"
  :enter="{ y: 0, opacity: 1, transition: { delay: 3500 } }">

[Learn More](https://sli.dev/guide/animations.html#motion)

</div>

---

# LaTeX

LaTeX is supported out-of-box powered by [KaTeX](https://katex.org/).

<br/>

Inline $\sqrt{3x-1}+(1+x)^2$

Block
$$
\begin{array}{c}

\nabla \times \vec{\mathbf{B}} -\, \frac1c\, \frac{\partial\vec{\mathbf{E}}}{\partial t} &
= \frac{4\pi}{c}\vec{\mathbf{j}}    \nabla \cdot \vec{\mathbf{E}} & = 4 \pi \rho \\

\nabla \times \vec{\mathbf{E}}\, +\, \frac1c\, \frac{\partial\vec{\mathbf{B}}}{\partial t} & = \vec{\mathbf{0}} \\

\nabla \cdot \vec{\mathbf{B}} & = 0

\end{array}
$$

<br/>

[Learn more](https://sli.dev/guide/syntax#latex)

---

# Diagrams

You can create diagrams / graphs from textual descriptions, directly in your Markdown.

<div class="grid grid-cols-3 gap-10 pt-4 -mb-6">

```mermaid {scale: 0.5}
sequenceDiagram
    Alice->John: Hello John, how are you?
    Note over Alice,John: A typical interaction
```

```mermaid {theme: 'neutral', scale: 0.8}
graph TD
B[Text] --> C{Decision}
C -->|One| D[Result 1]
C -->|Two| E[Result 2]
```

```plantuml {scale: 0.7}
@startuml

package "Some Group" {
  HTTP - [First Component]
  [Another Component]
}

node "Other Groups" {
  FTP - [Second Component]
  [First Component] --> FTP
}

cloud {
  [Example 1]
}


database "MySql" {
  folder "This is my folder" {
    [Folder 3]
  }
  frame "Foo" {
    [Frame 4]
  }
}


[Another Component] --> [Example 1]
[Example 1] --> [Folder 3]
[Folder 3] --> [Frame 4]

@enduml
```

</div>

[Learn More](https://sli.dev/guide/syntax.html#diagrams)


---
layout: center
class: text-center
---

# Learn More

[Documentations](https://sli.dev) · [GitHub](https://github.com/slidevjs/slidev) · [Showcases](https://sli.dev/showcases.html)
