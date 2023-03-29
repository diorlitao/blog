---
layout: home
layoutClass: 't-home-layout'

hero:
  name: 涛涛的
  text: 个人前端导航
  tagline: 用于学习技术和记录生活
  image:
    src: /logo.png
    alt: 涛涛物语
  actions:
    - text: 导航
      link: /nav/
    - text: 涛涛物语
      link: /life/
      theme: alt
    - text: 学习笔记
      link: /notes/
      theme: alt
    - text: 软件工具
      link: /utils/
      theme: alt
features:
  - icon: 📖
    title: 涛涛物语
    details: 整理常用知识点<br />如有异议按你的理解为主，不接受反驳
  - icon: 📘
    title: 源码阅读
    details: 了解各种库的实现原理<br />学习其中的小技巧和冷知识
  - icon: 💡
    title: 奇淫技巧
    details: 各种各样的奇淫技巧<br />配合 CV 大法来解决疑难杂症
  - icon: 🧰
    title: 提效工具
    details: 工欲善其事，必先利其器<br />记录开发和日常使用中所用到的软件、插件、扩展等
  - icon: 🐞
    title: 踩坑记录
    details: 那些年我们踩过的坑<br />总有一些让你意想不到的问题
  - icon: 💯
    title: 知行合一，得到功成。
    details: '<small class="bottom-small">一个前端小开发</small>'
---

<style>
/*爱的魔力转圈圈*/
.t-home-layout .image-src:hover {
  transform: translate(-50%, -50%) rotate(666turn);
  transition: transform 59s 1s cubic-bezier(0.3, 0, 0.8, 1);
}

.t-home-layout .details small {
  opacity: 0.8;
}

.t-home-layout .bottom-small {
  display: block;
  margin-top: 2em;
  text-align: right;
}
</style>
