---
title: Vue3 组合式 API 实践
description: Vue3 组合式 API 学习笔记
published: 2026-01-03
tags:
  - 前端开发
  - 前端工程化
  - 架构与思考
category: 前端开发
---

# Vue3 组合式 API 实践

Vue3 组合式 API 是 Vue3 最重要的新特性之一...

## 为什么选择组合式 API

- 更好的逻辑复用
- 更灵活的代码组织
- 更好的 TypeScript 支持

## setup 函数

```vue
<script setup>
import { ref, computed } from 'vue'

const count = ref(0)
const doubled = computed(() => count.value * 2)
</script>
```
