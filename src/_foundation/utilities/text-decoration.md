---
layout: default
permalink: /foundation/utilities/text-decoration
has-parent: /foundation/utilities/
title: Text decoration
---

# Text decoration

<div class="va-introtext" markdown="1">
Change the text-decoration.
</div>

<div class="site-showcase">
  {%
    include _showcase-header.html
    heading_level=2
    header="Text decoration"
    responsive=false
    css_property="text-decoration"
  %}
  <div class="vads-grid-row vads-u-flex-direction--column">
    <div class="site-showcase__col vads-grid-row vads-u-align-items--flex-start vads-u-border-top--0">
      <div class="vads-grid-col-12 tablet:vads-grid-col-6">
          <code class="code">.vads-u-text-decoration--none</code>
      </div>
      <div class="vads-grid-col-12 tablet:vads-grid-col-6">
        <a href="javascript:void();" class="vads-u-text-decoration--none">Link with no underline</a>
      </div>
    </div>
    <div class="site-showcase__col vads-grid-row vads-u-align-items--flex-start">
      <div class="vads-grid-col-12 tablet:vads-grid-col-6">
          <code class="code">.vads-u-text-decoration--underline</code>
      </div>
      <div class="vads-grid-col-12 tablet:vads-grid-col-6">
        <span class="vads-u-text-decoration--underline">Non-link with underline</span>
      </div>
    </div>
    <div class="site-showcase__col vads-grid-row vads-u-align-items--flex-start">
      <div class="vads-grid-col-12 tablet:vads-grid-col-6">
          <code class="code">.vads-u-text-decoration--line-through</code>
      </div>
      <div class="vads-grid-col-12 tablet:vads-grid-col-6">
        <span class="vads-u-text-decoration--line-through">strikethrough text</span>
      </div>
    </div>
  </div>
</div>

## Guidance

- Underlines are an important link affordance for users who may experience difficulties perceiving contrast. Remove the underline from links only when the context implies there is interaction.
- Do not use underlines for emphasis. Underlines imply interaction. Use bold text instead.
