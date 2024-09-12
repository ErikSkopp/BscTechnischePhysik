---
title: Technische Physik
toc: true
type: docs
---
{{< cards >}}
  {{< card link="../callout" title="Card with default tag color" tag="tag text" >}}
  {{< card link="../callout" title="Card with default red tag" tag="tag text" tagType="error" >}}
  {{< card link="../callout" title="Card with blue tag" tag="tag text" tagType="info" >}}
  {{< card link="../callout" title="Card with yellow tag" tag="tag text" tagType="warning" >}}
{{< /cards >}}
<!-- Das ist ein Text mit einer Fußnote[^2].

[^2]: Hier ist die Erklärung zur Fußnote. -->


{{< cards >}}
  {{< card link="/" title="Image Card" image="https://source.unsplash.com/featured/800x600?landscape" subtitle="Unsplash Landscape" >}}
  {{< card link="/" title="Local Image" image="/images/module/flowers-7276139_1280.jpg" subtitle="Raw image under static directory." >}}
  {{< card link="/" title="Local Image" image="images/space.jpg" subtitle="Image under assets directory, processed by Hugo." method="Resize" options="600x q80 webp" >}}
{{< /cards >}}