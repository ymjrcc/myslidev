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
      <li v-click class="leading-6 text-gray-200">人们将各种业余时间打造的产品或项目称为 “Side Project”。</li>
      <li v-click class="leading-6 text-gray-200">Side Project 的初始需求，往往来源于自己或身边人，最开始只要满足自己或者最小群体的需求就足够了。</li>
      <li v-click class="leading-6 text-gray-200">MVP(Minimum Viable Product)，最小可用产品，从产品的核心功能开始构建。</li>
      <li v-click class="leading-6 text-gray-200">一个 Side Project，无论最终能否给你带来回报，把自己的想法从 0 到 1 实现，本身就是一个快乐而充实的过程。</li>
    </ul>
  </div>
  <div class="flex-1 rounded-lg p-4 bg-gray-50 bg-opacity-20">
    <div v-click class="text-2xl title font-bold mb-2">Side Project 的目的</div>
    <ul class="text-gray-200">
      <li v-click>解决自己或别人的问题</li>
      <li v-click>练手，提高技术</li>
      <li v-click>赚钱</li>
      <li v-click>Just For Fun</li>
      <li v-click>……</li>
    </ul>
  </div>
</div>
<div class="rounded-lg p-4 bg-gray-50 bg-opacity-20 h-42">
<div v-click class="text-2xl title font-bold mb-2">举几个栗子</div>
<v-clicks>

- Apple 生态大量的独立开发者，通过 Side Project 给自己一份“睡后收入”
- Side Project 的最高境界，发展成 Main Project：Vue、[简书](https://www.jianshu.com/)
- 我的 Side Projects：[雪球神器](https://github.com/ymjrcc/xueqiu_crx)、[metro](https://ymjrcc.github.io/metro/)、我的人人

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

# 真的要开始吗？先问自己几个问题：

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

# 磨刀不误砍柴工：列一个需求清单 / Todolist

<div class="rounded-lg py-2 px-4 bg-gray-50 bg-opacity-20">
  <div class="mb-1">
    <span class="text-blue-300">分类拆解：</span>
    <span v-click class="text-base">将整个工程分门别类，然后细化成一个个小任务，巧用 TODO，做一个勾一个</span>
  </div>
  <div>
    <span class="text-blue-300">版本迭代：</span>
    <span v-click class="text-base">统筹规划，有排期和项目里程碑；想好再改，不要东一榔头西一棒</span>
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
# 产品演变：“我的人人”是如何从 0 到 1 的

<div class="rounded-lg p-6 bg-gray-500 bg-opacity-50 mt-6 text-blue-300">

- v0.0.0: <span v-click class="pl-2 text-white">有个需求——人人网要倒闭了，我要把我的发的状态都存下来</span>
- v0.0.1: <span v-click class="pl-2 text-white">实现方式——用笔记软件存太麻烦了，写个网页存下来吧</span>
- v0.1.0: <span v-click class="pl-2 text-white">加功能——有的状态带图片，图片存在相册里，那也要把相册存下来（路由）</span>
- v0.1.1: <span v-click class="pl-2 text-white">加功能——相册都有了，日志没有说不过去吧</span>
- v0.1.2: <span v-click class="pl-2 text-white">加功能——好友也是回忆的一部分，把好友信息也存下来</span>
- v0.2.0: <span v-click class="pl-2 text-white">页面这么多了，用状态页做首页不合适，再写个首页做总览</span>
- v0.2.1: <span v-click class="pl-2 text-white">重要的事件分散在各个页面里，按时间顺序捋出来，做个时间轴</span>
- v0.3.0: <span v-click class="pl-2 text-white">既然有了很多数据，做个可视化数据分析</span>
- v0.4.0: <span v-click class="pl-2 text-white">性能优化和用户体验</span>
- ……
- v1.0.0: <span v-click class="pl-2 text-white">产品上线</span>

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
# 开工准备

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

- React
- Ant Design
- echarts
- ……

</v-clicks>
</div>
</div>

<div class="absolute right-14 top-27 rounded-lg p-3 bg-gray-50 bg-opacity-20 w-90 h-100">
<div v-click class="text-xl text-blue-300 mb-2">忠告</div>
<v-clicks>

- 不要在准备工作上花太多时间
- “差生文具多”
- 不要陷入选择恐惧
- 干就完了

</v-clicks>

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

<div class="w-full flex">

<div class="rounded-lg px-3 py-2 bg-gray-50 bg-opacity-20 mt-3 mr-4 flex-1 h-105">
<div v-click class="text-xl text-blue-300 mb-2">不怕折腾，放心大胆地尝试最新技术</div>
<div>
<v-clicks>

- TailWind CSS → Windi CSS
- React 17 → React 18
- create-react-app → vite

</v-clicks>
</div>
</div>

<div class="rounded-lg px-3 py-2 bg-gray-50 bg-opacity-20 mt-3 mr-4 flex-1 h-105">
<div v-click class="text-xl text-blue-300 mb-2">使用工具，强行约束</div>
<div>
<v-clicks>

- [React.StrictMode](https://zhuanlan.zhihu.com/p/401329405)
- TypeScript + ts-standard

</v-clicks>
</div>
</div>

<div class="rounded-lg px-3 py-2 bg-gray-50 bg-opacity-20 mt-3 flex-1 h-105">
<div v-click class="text-xl text-blue-300 mb-2">要代码质量，不要天马行空</div>
<div>
<v-clicks>

- DRY：函数复用、组件模块抽取
- 良好的代码结构，代码优化、重构
- 逻辑与数据解耦

</v-clicks>
</div>
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
layout: image
image: "/img/bg7.jpg"
---

# 性能优化和用户体验

<div class="rounded-lg p-3 bg-gray-50 bg-opacity-20 mt-4 w-100">
  <div v-click class="text-xl text-blue-300 mb-2">优先级</div>
  <div v-click class="pl-4 pt-1">抓大放小，实现功能在前，完善细节在后</div>
</div>

<div class="rounded-lg p-3 bg-gray-50 bg-opacity-20 mt-6 w-100">
  <div v-click class="text-xl text-blue-300 mb-2">优化打包体积、First Paint</div>
  <div v-click class="pl-4 pt-3">source-map-explorer 分析模块模块空间占用</div>
  <div v-click class="pl-4 pt-3">import() 做代码分割</div>
  <div v-click class="pl-4 pt-3">依赖瘦身，善用但克制使用第三方库</div>
  <div v-click class="pl-8 pt-2 text-sm text-gray-300">杜绝层层封装（真的需要 echarts-for-xxx 吗）</div>
  <div v-click class="pl-8 pt-2 text-sm text-gray-300">不要为了一个小功能引入一个大依赖（dayjs）</div>
  <div v-click class="pl-8 pt-2 text-sm text-gray-300">能自己实现就自己实现（热力图、瀑布流）</div>
  <div v-click class="pl-8 pt-2 pb-3 text-sm text-gray-300">用图片代替没有交互的地图</div>
</div>

<div class="absolute right-14 top-25 rounded-lg p-3 bg-gray-50 bg-opacity-20 w-113 h-95">
  <div v-click class="text-xl text-blue-300 mb-2">提升用户体验</div>
  <div v-click class="pl-4 pt-4">React.lazy + Suspence 实现系统级的自动 loading</div>
  <div v-click class="pl-4 pt-4">统一的设计语言，提高 UI 审美</div>
  <div v-click class="pl-4 pt-4">多场景支持（如响应式布局、dark 模式等）</div>
  <div v-click class="pl-4 pt-4">考虑性价比，拿掉开销大但意义不大的模块</div>
  <div v-click class="pl-4 pt-4"> 如果要做开源：</div>
  <div v-click class="pl-8 pt-3 text-sm text-gray-300">完善的教程和文档</div>
  <div v-click class="pl-8 pt-2 text-sm text-gray-300">良好的兼容性</div>
  <div v-click class="pl-8 pt-2 text-sm text-gray-300">i18n</div>
  <div v-click class="pl-8 pt-2 text-sm text-gray-300">收集用户反馈，持续迭代优化</div>
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
# 一些心得体会

<div class="w-full flex">

<div class="rounded-lg px-3 py-2 bg-gray-50 bg-opacity-20 mr-4 flex-1 h-105">
<div v-click class="text-xl text-blue-300 mb-1">做笔记很重要！</div>
<div>
<v-clicks>

- 整理灵感、管理需求
- 提炼保存可复用的代码片段
- 记录使用工具的技巧

</v-clicks>
</div>
</div>

<div class="rounded-lg px-3 py-2 bg-gray-50 bg-opacity-20 mr-4 flex-1">
<div v-click class="text-xl text-blue-300 mb-1">拥抱社区和开源</div>
<div>
<v-clicks>

- 用社群 / issue 提问，反馈 bug 和问题（[如何提问](https://www.yuque.com/docs/share/aedf72a6-e5e5-4bf4-b95f-12c19dddffdd)）
- 发现 bug 若有能力自行修复，可提 pr 反哺社区
- 迭代成熟后，考虑开源自己的作品

</v-clicks>
</div>
</div>

<div class="rounded-lg p-3 bg-gray-50 bg-opacity-20 flex-1">
<div v-click class="text-xl text-blue-300 mb-1">“上价值”</div>
<div>
<v-clicks>

- 在岸上永远学不会游泳
- 汝果欲学诗，功夫在诗外
- 种一棵树最好的时间是十年前，其次是现在
- 自我驱动，兴趣是最好的老师

</v-clicks>
</div>
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
layout: image
image: "/img/bg9.jpg"
---

# 工具推荐

<div class="rounded-lg p-6 bg-gray-50 bg-opacity-20 text-blue-300 mt-6 h-100">
<v-clicks>

- Logseq <span class="pl-4 text-white">笔记管理（markdown，双链，本地存储，隐私优先）</span>
- VS Code Project Manager<span class="pl-4 text-white">VS Code 多项目切换神器</span>
- github.dev<span class="pl-4 text-white">将 GitHub 仓库变成在线 VS Code</span>
- source-map-explorer<span class="pl-4 text-white">基于 source-map 的可视化代码分析溯源工具</span>
- slidev<span class="pl-4 text-white">用 markdown 和 html 语言生成在线 PPT</span>
- unsplash<span class="pl-4 text-white">免费高清图库</span>
- TinyPNG for Mac<span class="pl-4 text-white">无损压缩图片客户端工具</span>

</v-clicks>
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
