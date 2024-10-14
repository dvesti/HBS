---
authors:
- HB
- HugoMods
categories:
- Content
date: "2023-11-26T16:36:24+08:00"
description: This article offers some examples about math typesetting via KaTeX.
draft: false
featured: true
images:
- https://example-images.razonyang.com/math.webp?width=1920&height=1280
noindex: false
pinned: false
series:
- Examples
tags:
- Math
- KaTeX
title: Math Typesetting
---

## Using KaTeX Code Block

````markdown
```katex
f(a,b,c) = (a^2+b^2+c^2)^3
```
````

```katex
f(a,b,c) = (a^2+b^2+c^2)^3
```

## Using KaTeX Shortcode

```markdown
{{</* katex */>}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{</* /katex */>}}
```

{{< katex >}}
f(x) = \int_{-\infty}^\infty\hat f(\xi)\,e^{2 \pi i \xi x}\,d\xi
{{< /katex >}}

## Further Reading

- [KaTeX official site](https://katex.org/)
- [Hugo KaTeX module](https://hugomods.com/docs/content/katex/)
