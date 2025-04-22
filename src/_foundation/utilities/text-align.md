---
layout: default
permalink: /foundation/utilities/text-align
has-parent: /foundation/utilities/
title: Text align
---

# Text align

<div class="va-introtext" markdown="1">
Change the alignment of text or elements. This utility also [responsive prefixes](#responsive-prefixes).
</div>

<div class="site-showcase">
  {%
    include _showcase-header.html
    heading_level=2
    header="Text align"
    responsive=true
    css_property="text-align"
  %}
  <div class="vads-grid-row vads-u-flex-direction--column">
    {% for item in site.data.text-align.alignments %}
      {% include text-align-example.html
        name=item.name
        index=forloop.index
      %}
    {% endfor %}
  </div>
</div>

## Responsive prefixes

Add a responsive breakpoint prefix separated with a : to target a utility at a responsive breakpoint and higher, following a mobile-first methodology.

<div class="site-showcase">
{% include_relative html/text-align.html %}
</div>

{% include snippet.html content='html/text-align.html' %}

### Example

```html
<div class="vads-u-text-align--left desktop-lg:vads-u-text-align--center">
```
{% include _breakpoint-names.html %}