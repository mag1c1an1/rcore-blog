---
title: yjymosheng
date: 2024-04-30 01:44:25
tags:
      - author:yjymosheng
      - repo:https://github.com/yjymosheng/blog
---

## 初次认真学习rust每一个点 ##

通过某些渠道，第一次了解到操作系统训练营，以前我也有用rust写过一些内容，但严格来说这是我的第一次正式学习rust。学习了很多的内容，了解到了闭包，函数式编程，拓展了我的知识面，我第一次见到结构如此清晰的语言。

## 所有权的理解 ##

众所周知，rust很贪。所有权是其中的灵魂。我认为，其本质就是“作茧自缚”，减少了许多东西，又为方便开发与调试添加了许多东西。这些设计减少了许多的错误。所以简单的把所有权当作单线程的脑子就行，不要给它过多的行为。

## 错误处理中的Option Result ##


- Option 用于表达可能存在或者不存在的值，它有两种可能的状态：Some(值) 和 None。当你不确定一个值是否存在时，可以使用 Option 来处理这种情况。

- Result 则用于表达可能的操作成功或失败的结果，它有两种可能的状态：Ok(值) 和 Err(错误)。当你需要处理可能出现错误的情况时，可以使用 Result 来处理这种情况。

## 令人耳目一新的枚举类型 match ##

在 Rust 中，枚举类型是一种非常强大的数据结构，它可以用来表达一组相关的值。而使用 match 关键字可以让我们更加灵活地处理枚举类型的值，使得代码更加清晰易懂。

match 表达式可以用来匹配枚举类型的不同变体，并根据不同的情况执行相应的代码逻辑。这种模式匹配的方式让代码的逻辑结构清晰明了，同时也增强了代码的可读性和可维护性。

## 我的收获 ##

通过学习 Rust，我收获了很多。不仅仅是语言本身的特性和语法，更重要的是 Rust 给我带来的编程思维方式的转变。在学习 Rust 的过程中，我更加注重代码的安全性和可靠性，学会了如何利用 Rust 的各种特性来编写更加健壮的程序。

另外，通过与社区的交流和分享，我还了解到了很多其他开发者的经验和见解，这也让我受益匪浅。总的来说，学习 Rust 是一次非常有意义的经历，我相信在将来的工作和项目中，我会继续运用 Rust 的知识和思想，为我的编程生涯注入新的活力和动力。

