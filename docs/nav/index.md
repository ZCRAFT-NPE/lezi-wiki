---
layoutClass: m-nav-layout
outline: [1, 2, 3, 4]
---

<script setup>
import { NAV_DATA } from './data'
</script>
<style src="./index.scss"></style>

# Wiki 导航

::: tip
为了 LeziWiki 的合规性，已临时下架之前由各大贡献者贡献的文章，待审核完成并处理完隐私内容后，将重新上线。NeoLeziWiki 将注重事件记录，将不会记录隐私内容。
:::

<MNavLinks v-for="{title, items} in NAV_DATA" :title="title" :items="items"/>

<br />

::: tip
该导航模板来自 [maomao](https://github.com/maomao1996) 版权声明：<https://github.com/maomao1996/vitepress-nav-template>
:::
