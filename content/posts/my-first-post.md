---
title: "Coby Testing Mermaid Diagram"
date: 2022-07-09T03:46:56Z
draft: false
---

This is coby testing out a post 

```
{{</*mermaid align="left"*/>}}
graph LR;
    A[Coby] -->|Testing| B(Mermaid)
    B(Mermaid) --> C{Push to Github}
    C -->|One| D[Github creates Container]
    C -->|Two| E[Builds & Deploys Website on Push]
{{</* /mermaid */>}}
```

renders as

{{<mermaid align="left">}}
graph LR;
    A[Coby] -->|Testing| B(Mermaid)
    B(Mermaid) --> C{Push to Github}
    C -->|One| D[Github creates Container]
    C -->|Two| E[Builds & Deploys Website on Push]
{{</mermaid>}}