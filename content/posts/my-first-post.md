---
title: "Coby Testing Mermaid Diagram"
date: 2022-07-09T03:46:56Z
draft: false
---

This is a post by Coby testing out a mermaid functionality.

This is what you would type in the .MD file:
```
{{</*mermaid align="left"*/>}}
graph LR;
    A[Coby] -->|Testing| B(Mermaid)
    B(Mermaid) --> C{Push to Github}
    C -->|One| D[Github creates Container]
    C -->|Two| E[Builds & Deploys Website on Push]
{{</* /mermaid */>}}
```

{{< line_break >}}

Thereafter Hugo will render it as follows:
{{<mermaid align="left">}}
graph LR;
    A[Coby] -->|Testing| B(Mermaid)
    B(Mermaid) --> C{Push to Github}
    C -->|One| D[Github creates Container]
    C -->|Two| E[Builds & Deploys Website on Push]
{{</mermaid>}}

{{< line_break >}}
{{< line_break >}}
{{< line_break >}}

Testing out Model Embed

{{< f360 url=https://a360.co/3Fn3rdO size=M >}}