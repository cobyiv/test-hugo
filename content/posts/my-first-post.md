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

{{< iframe url="https://dowbuilt.egnyte.com/dl/TZdYo9e8YM" w="800" h="600" >}}

Testing out Model Embed

{{< f360 url=https://dowbuilt1.autodesk360.com/shares/public/SH35dfcQT936092f0e43fc5eb33fe5578c6c size=M >}}