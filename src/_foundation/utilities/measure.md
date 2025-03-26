---
layout: default
permalink: /foundation/utilities/measure
has-parent: /foundation/utilities/
title: Measure
---

# Measure

<div class="va-introtext" markdown="1">
Set the `max-width` by number of characters per line using `ch` units instead of pixel values. Measure classes include [responsive prefixes](#responsive-prefixes).
</div>

In other words, as the font size increases, the pixel width increases.


<div class="site-showcase">
  {%
    include _showcase-header.html
    heading_level=2
    header="Measure"
    responsive=true
    css_property="max-width (ch)"
  %}
  <div class="vads-grid-row">
    {% for item in site.data.measures.measures %}
      <div class="site-showcase__col vads-grid-col-12 {% if forloop.index == 1 %}vads-u-border-top--0{% endif %}">
        <div class="vads-u-display--flex vads-u-justify-content--space-between">
          <code class="code">.vads-u-measure--{{ item.name }}</code>
          <span class="site-utility-value">{{ item.value }}</span>
        </div>

        <div class="vads-u-display--flex vads-u-align-items--center vads-u-border-top--1px vads-u-border-color--gray-lightest vads-u-margin-top--3">
          <p class="vads-u-measure--{{ item.name }} vads-u-border-bottom--5px vads-u-border-color--secondary-light">To fulfill President Lincoln's promise “To care for him who shall have borne the battle, and for his widow, and his orphan” by serving and honoring the men and women who are America’s Veterans.</p>
        </div>

        <div class="vads-u-display--flex vads-u-align-items--center">
          <p class="vads-u-font-size--lg vads-u-measure--{{ item.name }} vads-u-border-bottom--5px vads-u-border-color--secondary-light">To fulfill President Lincoln's promise “To care for him who shall have borne the battle, and for his widow, and his orphan” by serving and honoring the men and women who are America’s Veterans.</p>
        </div>
      </div>
    {% endfor %}
  </div>
</div>

## Responsive prefixes

Add a responsive breakpoint prefix separated with a : to target a utility at a responsive breakpoint and higher, following a mobile-first methodology.

### Example

```html
<div class="tablet:vads-u-measure--5 desktop-lg:vads-u-measure--1">
```
{% include _breakpoint-names.html %}