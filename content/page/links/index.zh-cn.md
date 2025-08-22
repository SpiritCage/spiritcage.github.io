---
title: 链接
slug: "links"
layout: "links"
links:
  - title: GitHub
    description: GitHub 是全球最大的软件开发平台。
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
  - title: TypeScript
    description: TypeScript 是 JavaScript 的类型超集，可编译为纯 JavaScript。
    website: https://www.typescriptlang.org
    image: ts-logo-128.jpg
  - title: TeX Functions
    description: TeX 函数的在线参考
    website: https://katex.org/docs/supported.html
    image: https://katex.org/img/og_logo.png
menu:
    main: 
        weight: -50
        params:
            icon: link

comments: false
---

To use this feature, add `links` section to frontmatter.

This page's frontmatter:

```yaml
links:
  - title: GitHub
    description: GitHub is the world's largest software development platform.
    website: https://github.com
    image: https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png
  - title: TypeScript
    description: TypeScript is a typed superset of JavaScript that compiles to plain JavaScript.
    website: https://www.typescriptlang.org
    image: ts-logo-128.jpg
```

`image` field accepts both local and external images.