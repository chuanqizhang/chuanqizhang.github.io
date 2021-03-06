---
layout:     post
title:      "Hello world"
subtitle:   "Welcome!"
date:       2018-09-05 08:00:00
author:     "Chuanqi"
header-img: "img/bg/hello_world.jpg"
catalog: true
tags:
    - Essay
---

# Hello, I'm Chuanqi

This is a guide for Markdown, also the first post in my blog.

Markdown is a widespread and powerful automated typesetting system so that you'll never worry about the resultant typesetting but just need focus on the content itself!

Hello, I'm Chuanqi. Now let me introduce briefly:

- Basic Markdown
- Syntax Highlighting
- LaTeX Rendering

## Basic Markdown


> Markdown is a lightweight markup language with plain text formatting syntax.    —— [Wikipedia](https://en.wikipedia.org/wiki/Markdown)


### Tables

| Items       |     Price |  Number  |
| :------- | -----: | :--: |
| Computer | 1600 dollars |  5   |
| Phone    |   12 dollars |  12  |
| Pipe     |    1 dollar | 234  |

### Lists

#### Unordered Lists

- car
- train
- plane

#### Ordered Lists

1. car
2. train
3. plane

#### Nested Lists

- transposition
  - car
    - truck
    - coach
  - train
  - plane
- road
  - road1
  - road2

##  Syntax Highlighting

The codes are rendered by [highlight.js](https://highlightjs.org/), which is shown as below:

**C**

```c
#include <stdio.h>
int main()
{
    printf("Hello World!/n");
    return 0;
}
```

**Java**

```java
class Hello
{
    public static void main(String ars[])
    {
        System.out.print("Hello World!/n");
    }
}
```

## LaTeX Rendering

The math formulas are rendered by [MathJax](https://www.mathjax.org/), which is shown as below：

It supports the inline mode $\sqrt{a+b}$ and the display mode

$$
x=\frac{-b\pm\sqrt{b^2-4ac}}{2a}
$$
