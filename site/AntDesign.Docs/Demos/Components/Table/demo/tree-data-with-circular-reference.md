---
order: 17.1
title:
  en-US: Tree Data with Circular Reference
  zh-CN: 带有循环引用的树形数据
---

## zh-CN

在展示树形数据时，Table组件能够处理父子数据之间的循环引用。

当设置了 DefaultExpandAllRows 时，将按照 DefaultExpandMaxLevel 来限制展开的级数，避免因循环引用导致应用陷入死循环。

DefaultExpandMaxLevel 的默认值为 4。

## en-US

`Table` can mitigate circular references in tree data.

When you are using `DefaultExpandAllRows`, the max expand level is limited by `DefaultExpandMaxLevel` to avoid endless looping.

The default value of `DefaultExpandMaxLevel` is 4.

