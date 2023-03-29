---
layoutClass: t-nav-layout
outline: [2, 3, 4]
---

<script setup>
import TNavLinks from './components/TNavLinks.vue'

import { NAV_DATA } from './data'
</script>
<style src="./index.scss"></style>

# 前端导航

::: tip
该导航由 [diorlitao](https://github.com/diorlitao) 开发，如有引用、借鉴的请保留版权声明：<https://github.com/diorlitao/blog>
:::

<TNavLinks v-for="{title, items} in NAV_DATA" :title="title" :items="items"/>

<br />

::: tip
该导航由 [diorlitao](https://github.com/diorlitao) 开发，如有引用、借鉴的请保留版权声明：<https://github.com/diorlitao/blog>
:::
