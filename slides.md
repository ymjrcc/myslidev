---
theme: seriph
title: 程序员如何拥有一个 Side Project？
background: /img/bg.jpg
class: text-center
highlighter: shiki
lineNumbers: false
colorSchema: dark
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
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
这是一个偏体验类的分享

在场有多少人上学的时候玩过人人网？

半个月前，我有了一个新想法，趁人人网倒闭之前，把我大学四年发的状态都保存下来。

这半个多月里，利用空闲时间，逐步把这件事给完成得差不多了，算是做了个 side project。借这个机会，给大家分享一下做这件事的过程，以及我的一些想法。
-->

---
layout: image
image: /img/bg1.jpg
---

<div class="flex mb-6">
  <div class="w-145 mr-6 rounded-lg p-4 bg-gray-800/40">
    <div v-click class="text-2xl title font-bold mb-2">什么是 Side Project</div>
    <ul>
      <li v-click class="leading-6 text-gray-200">人们将各种业余时间打造的产品或项目称为 “Side Project”。</li>
      <li v-click class="leading-6 text-gray-200">Side Project 的初始需求，往往来源于自己或身边人，最开始只要满足自己或者最小群体的需求就足够了。</li>
      <li v-click class="leading-6 text-gray-200">MVP(Minimum Viable Product)，最小可用产品，从产品的核心功能开始构建。</li>
      <li v-click class="leading-6 text-gray-200">一个 Side Project，无论最终能否给你带来回报，把自己的想法从 0 到 1 实现，本身就是一个快乐而充实的过程。</li>
    </ul>
  </div>
  <div class="flex-1 rounded-lg p-4 bg-gray-800/40">
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
<div class="rounded-lg p-4 bg-gray-800/40 h-42">
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

<!--
雪球神器：为了解决我自己看雪球网的需求

metro：为了解决我朋友每天发微博记录地铁通车时间的需求（就算是一个非常简单的页面，只要能够满足用户的需求，就是有意义的）

-->

---
layout: image
image: "/img/bg2.jpg"
---

<v-click>

# 真的要开始吗？先问自己几个问题：

</v-click>

<br/>

<div class="rounded-lg p-6 bg-gray-800/40">
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
<div class="rounded-lg p-6 bg-gray-800/40">
  <h2 v-click class="text-green-500 italic mb-4">不，你有！</h2>
  <div class="text-gray-300 text-sm italic" v-click>✅ 需求驱动 ✅ 兴趣驱动 ✅ 善用零碎时间</div>
</div>

<!--

这句话是我之前参与一个前端大佬发起的每周写一篇技术博客的 FAQ 里借鉴过来的。

当时他的问答清单里有一个就是，我没有时间怎么办？他很简明扼要地回答：“不，你有！”

只要你真心想做一件事，时间肯定会有的。如果非要说没时间，那只能说明这件事在你心里优先级没有那么靠前

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

<!-- 

非常重要，直接决定项目成败

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
image: "/img/bg8.jpg"
---
# 产品演变：“我的人人”是如何从 0 到 1 的

<div class="rounded-lg p-6 bg-gray-800/40 mt-6 text-blue-300">

- v0.0.0: <span v-click class="pl-2 text-white">有个需求——人人网看起来快要倒闭了，我要把我的发的状态都存下来</span>
- v0.0.1: <span v-click class="pl-2 text-white">实现方式——用笔记软件一条一条复制保存太麻烦了，不如写个网页存下来</span>
- v0.1.0: <span v-click class="pl-2 text-white">加功能——有的状态带图片，图片存在相册里，那也要把相册存下来（添加路由）</span>
- v0.1.1: <span v-click class="pl-2 text-white">加功能——相册都有了，日志没有说不过去吧，顺便把日志页也加了</span>
- v0.1.2: <span v-click class="pl-2 text-white">加功能——好友也是回忆的一部分，把好友信息也存下来</span>
- v0.2.0: <span v-click class="pl-2 text-white">页面这么多了，再用状态页做首页不合适，写个首页</span>
- v0.2.1: <span v-click class="pl-2 text-white">重要的事件分散在各个页面里，按时间顺序捋出来，做个时间轴页</span>
- v0.3.0: <span v-click class="pl-2 text-white">既然有了很多数据，那可以做个可视化数据分析</span>
- v0.4.0: <span v-click class="pl-2 text-white">考虑性能优化和用户体验</span>
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

<div class="rounded-lg p-4 bg-gray-800/40 mt-6">
  <img v-click src="/img/mind.png" />
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

<!-- 

跳转到产品页面粗略讲一下

 -->

---
layout: image
image: "/img/bg4.jpg"
---
# 开工准备

<div class="rounded-lg p-3 bg-gray-800/40 mt-6 w-120">
<div v-click class="text-xl mb-2 rounded inline-block bg-blue-400/40 px-4 py-2px">工欲善其事，必先利其器：准备合适的工具</div>
<div class="ml-6">
<v-clicks>

- 代码托管：GitHub Private Repository
- 编辑器：VS Code + 项目管理器插件
- 包管理工具：yarn
- 需求与进度管理、笔记记录：Logseq

</v-clicks>
</div>
</div>

<div class="rounded-lg p-3 bg-gray-800/40 mt-6 w-120">
<div v-click class="text-xl mb-2 rounded inline-block bg-blue-400/40 px-4 py-2px">怎么舒服怎么来：选择最适合自己的技术栈</div>
<div class="ml-6">
<v-clicks>

- React（create-react-app）
- TypeScript
- Ant Design
- echarts

</v-clicks>
</div>
</div>

<div class="absolute right-14 top-27 rounded-lg p-3 bg-gray-800/40 w-90 h-100">
<div v-click class="text-xl mb-2 rounded inline-block bg-blue-400/40 px-4 py-2px">忠告</div>
<div class="ml-6">
<v-clicks>

- 不要在准备工作上花太多时间
- “差生文具多”
- 不要陷入选择恐惧
- 先用起来，不合适再换
- 干就完了！

</v-clicks>
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
image: "/img/bg5.jpg"
---

<div class="text-3xl text-gray-400 mb-1">Coding 原则 1：<span class="text-blue-300">不怕折腾，放心大胆地尝试最新技术</span></div>

<div class="w-full flex">

<div v-click="1" class="rounded-lg px-3 py-2 bg-gray-800/40 mt-3 mr-4 flex-1 h-110">
<div class="text-xl mb-1 rounded bg-blue-400/40 text-center">TailWind CSS → Windi CSS</div>

<div>

```html {all|all|1|7-11|2|12-16|all}
<div class="flex p-4 rounded">
  <span class="text-xl text-white">
  </span>
</div>

<style>
div{
  display: flex;
  padding: 1em;
  border-radius: 0.25rem;
}
span{
  font-size: 1.25rem;
  line-height: 1.75rem;
  color: #fff;
}
</style>
```
</div>

<div class="mt-2"><a target="_blank" href="https://www.tailwindcss.cn/">TailWind CSS</a>: 从此告别 CSS 文件</div>
<div class="mt-2"><a target="_blank" href="https://windicss.org/guide/migration.html">Windi CSS</a>: 更小、更快、更强</div>


</div>

<div v-click="7" class="rounded-lg px-3 py-2 bg-gray-800/40 mt-3 mr-4 flex-1">
<div class="text-xl mb-1 rounded bg-blue-400/40 text-center">升级 React 18 遇到的坑</div>
<ul>
<li>3 月中旬项目启动，3 月底 React 发布了新版本</li>
<li>为体验新版本特性，从 v17.0.2 升级到 v18.0.0</li>
<li>遇到 Ant Design 多个组件不兼容的问题</li>
<li>提 <a href="https://github.com/ant-design/ant-design/issues?q=author%3Aymjrcc" target="_blank">issues</a>，反馈问题</li>
<li>版本回退 or 寻找临时解决方案</li>
</ul>
</div>

<div v-after class="rounded-lg px-3 py-2 bg-gray-800/40 mt-3 mr-4 flex-1">
<div class="text-xl mb-1 rounded bg-blue-400/40 text-center">如何在开发中更换脚手架</div>
<ul>
<li>由于惯性选择 create-react-app，热更新速度慢</li>
<li>打算换成 <a href="https://cn.vitejs.dev/" target="_blank">vite</a> (速度更快，性能更好)</li>
<li>先开一个新仓库，成功运行 vite</li>
<li>将原仓库逻辑代码一点一点迁移过去</li>
<li>注意两个框架<a href="https://github.com/ymjrcc/myrenren/commit/25b408619353110d877379246a861780c02d0407" target="_blank">不兼容之处</a>，仔细修改</li>
<li>将新仓库代码覆盖原仓库，开个分支备份原仓库</li>
</ul>
</div>

</div>

<!-- 

举 3 个例子

不用在 js 和 css 文件间跳来跳去，非常方便复用，写更少的代码，不用绞尽脑汁想 class name

 -->

---
layout: image
image: "/img/bg5.jpg"
---

<div class="text-3xl text-gray-400 mb-1">Coding 原则 2：<span class="text-blue-300">使用工具，强行约束</span></div>

<div class="rounded-lg px-3 py-2 bg-gray-800/40 mt-3 h-105">

<div v-click class="mb-4 pb-4 border-b border-gray-100/20">
<div class="text-xl mb-2 rounded bg-blue-400/40 inline-block px-4 py-2px">
<a href="https://zhuanlan.zhihu.com/p/401329405" target="_blank">React.StrictMode</a>
</div>
<div class="w-96">

```jsx
import { StrictMode } from 'react'

const App = () => (
  <StrictMode>
    <App />
  </StrictMode>
)
```

</div>

</div>

<div v-click class="mb-4 pb-4 border-b border-gray-100/20">
<div class="text-xl mb-2 rounded bg-blue-400/40 inline-block px-4 py-2px">TypeScript</div>
</div>

<div v-click>
<div class="text-xl mb-2 rounded bg-blue-400/40 inline-block px-4 py-2px">ts-standard</div>
<div class="text-md text-gray-200 pl-4">
  TypeScript Style Guide, with linter and automatic code fixer based on 
  <a href="https://standardjs.com/index.html#why-should-i-use-javascript-standard-style" target="_blank">StandardJS</a>
</div>
</div>

</div>

<!-- 

StrictMode，后面埋了一个坑

ts 给人安全感,用了之后再写 js 会觉得非常不踏实

传统的 eslint 可配置项非常多，导致代码千人千面，引入新的问题

ts-standard 到底单引号还是双引号，空 2 格还是空 4 格，通通不用想，只有我这一种标准，照着写就好了

 -->

---
layout: image
image: "/img/bg5.jpg"
---

<div class="text-3xl text-gray-400 mb-1">Coding 原则 3：<span class="text-blue-300">不要放松对代码质量的要求</span></div>

<div class="rounded-lg p-4 bg-gray-800/40 mt-3 h-105">

<div v-click class="mb-4 pb-4 border-b border-gray-100/20">
<div class="text-xl mb-2 rounded bg-blue-400/40 inline-block px-4 py-2px">DRY：Don't Repeat Yourself</div>
<div class="text-md text-gray-200 pl-4 pt-2">@/utils 函数复用</div>
<div class="text-md text-gray-200 pl-4 pt-2">@/components 组件抽取</div>
<div class="text-md text-gray-200 pl-4 pt-2">npm 模块导入</div>
</div>

<div v-click class="mb-4 pb-4 border-b border-gray-100/20">
<div class="text-xl mb-2 rounded bg-blue-400/40 inline-block px-4 py-2px">代码优化</div>
<div class="text-md text-gray-200 pl-4 pt-2">清晰的代码结构</div>
<div class="text-md text-gray-200 pl-4 pt-2">持续重构</div>
</div>

<div v-click>
<div class="text-xl mb-2 rounded bg-blue-400/40 inline-block px-4 py-2px">逻辑与数据解耦</div>
<div class="text-md text-gray-200 pl-4 pt-2">有利于打包</div>
<div class="text-md text-gray-200 pl-4 pt-2">方便移植复用</div>
</div>

</div>

---
layout: image
image: "/img/bg7.jpg"
---

# 前端性能优化

<div class="rounded-lg p-3 bg-gray-800/40 mt-4 w-100 h-102">
  <div v-click class="text-xl mb-2 rounded bg-blue-400/40 inline-block px-4 py-2px">First Paint</div>
  <div v-click class="pl-4 py-2">import() 做代码分割</div>
  <div class="ml-4" v-click>

```jsx
import { lazy } from 'react'
const Home = lazy(() => import('./pages/Home'))
```

  </div>
  <div v-click class="pl-4 pt-4 pb-2">source-map-explorer 分析模块空间占用</div>
  <img v-click class="ml-4 w-19/20" src="/img/source-map-explorer.png" />
</div>

<div class="absolute right-14 top-25 rounded-lg p-3 bg-gray-800/40 w-110 h-65">
  <div v-click class="text-xl mb-2 rounded bg-blue-400/40 inline-block px-4 py-2px">减小打包体积</div>
  <div v-click class="pl-4 pt-4">依赖瘦身，善用但克制使用第三方库</div>
  <div v-click class="pl-4 pt-4">杜绝层层封装（真的需要 echarts-for-xxx 吗）</div>
  <div v-click class="pl-4 pt-4">不要为了一个小功能引入一个大依赖（dayjs）</div>
  <div v-click class="pl-4 pt-4">能自己实现就自己实现（热力图、瀑布流）</div>
  <div v-click class="pl-4 pt-4">用图片代替没有交互的地图</div>
</div>

<div class="absolute right-14 bottom-10 rounded-lg p-3 bg-gray-800/40 w-110 h-30">
  <div v-click class="text-xl mb-2 rounded bg-blue-400/40 inline-block px-4 py-2px">注意优先级</div>
  <div v-click class="pl-4 pt-4">抓大放小，实现功能在前，完善细节在后</div>
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

<!-- 

import() 在后面讲用户体验的时候还会提到

演示 sme 在项目中的应用

 -->

---
layout: image
image: "/img/bg7.jpg"
---

# 提升用户体验

<div class="flex">

<div class="rounded-lg p-3 bg-gray-800/40 mr-4 flex-1">
  <div v-click class="text-xl mt-2 rounded bg-blue-400/40 inline-block px-4 py-2px">代码层面</div>
  <div v-click class="pl-4 pt-4">React.lazy + Suspence 实现系统级的自动 loading</div>
  <div v-click class="text-xl mt-6 rounded bg-blue-400/40 inline-block px-4 py-2px">设计层面</div>
  <div v-click class="pl-4 pt-4">统一的设计语言，提高 UI 审美</div>
  <div v-click class="text-xl mt-6 rounded bg-blue-400/40 inline-block px-4 py-2px">需求层面</div>
  <div v-click class="pl-4 pt-4">多场景支持（如响应式布局、dark 模式等）</div>
  <div v-click class="pl-4 pt-4 pb-4">考虑性价比，拿掉开销大但意义不大的模块</div>
</div>

<div class="rounded-lg p-3 bg-gray-800/40 flex-1">
  <div v-click class="text-xl mt-2 rounded bg-blue-400/40 inline-block px-4 py-2px"> 如果要做开源</div>
  <div v-click class="pl-4 pt-4">完善的教程和文档</div>
  <div v-click class="pl-4 pt-4">良好的兼容性</div>
  <div v-click class="pl-4 pt-4">i18n</div>
  <div v-click class="pl-4 pt-4">收集用户反馈，持续迭代优化</div>
</div>

</div>

<style>
h1 {
  padding-bottom: 25px;
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

<div class="rounded-lg px-3 py-2 bg-gray-800/40 mr-4 flex-1 h-105">
<div v-click class="text-xl mb-1 rounded bg-blue-400/40 inline-block px-4 py-1">做笔记很重要！</div>
<div>
<v-clicks>

- 整理灵感、管理需求
- 提炼保存可复用的代码片段
- 记录使用工具的技巧

</v-clicks>
</div>
</div>

<div class="rounded-lg px-3 py-2 bg-gray-800/40 mr-4 flex-1">
<div v-click class="text-xl mb-1 rounded bg-blue-400/40 inline-block px-4 py-1">拥抱社区和开源</div>
<div>
<v-clicks>

- 用社群 / issue 提问，反馈 bug 和问题（[如何提问](https://www.yuque.com/docs/share/aedf72a6-e5e5-4bf4-b95f-12c19dddffdd)），代码复现推荐使用 [stackblitz](https://stackblitz.com/)
- 发现 bug 若有能力自行修复，可提 pr 反哺社区
- 迭代成熟后，考虑开源自己的作品

</v-clicks>
</div>
</div>

<div class="rounded-lg p-3 bg-gray-800/40 flex-1">
<div v-click class="text-xl mb-1 rounded bg-blue-400/40 inline-block px-4 py-1">“上价值”</div>
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

<div class="rounded-lg p-6 bg-gray-800/40 text-blue-300 mt-6 h-100">
<v-clicks>

- Logseq <span class="pl-4 text-white">笔记管理（markdown，双链，本地存储，隐私优先）</span>
- VS Code Project Manager<span class="pl-4 text-white">VS Code 多项目切换神器</span>
- github.dev<span class="pl-4 text-white">将 GitHub 仓库变成在线 VS Code</span>
- source-map-explorer<span class="pl-4 text-white">基于 source-map 的可视化代码分析溯源工具</span>
- [stackblitz](https://stackblitz.com/) <span class="pl-4 text-white">基于 VS Code 的在线开发/代码分享工具</span>
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
