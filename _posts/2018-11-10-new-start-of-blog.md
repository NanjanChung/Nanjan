---
layout: post
title:  "Welcome to Jekyll!"
---

# Java學習紀錄 (1)

## Comparable interface / Comparator interface
> - Java提供用以幫助sorting的interfaces
> - 習慣上，Comparable用於**自然排序**，Comparator用於**控制排序**
> - Arrays 和 Collections class有多種多載的sort方法，大致上分為兩類
>   - 以單一array作為參數，ex: `Arrays.sort(nums) // nums is a integer array`
>   - 以一個array和一個Comparator作為參數，ex: `Collections.sort(nums, new selfComparator())`

## Sort 方法

