---
layout: page
title: Katja Berčič | Other
---

{% assign posters = site.data.posters %}

# Other

I have a design ~~problem~~ hobby.

## Posters

{% for poster in posters %}
<div class="poster">
    <a href="/images/{{ poster.file }}"><img src="/images/{{ poster.file }}" /></a>
</div>
{% endfor %}
<div class="clr"></div>

## Prehistory

<div class="captioned-poster">
<div class="poster">
    <a href="/images/upm-2023.png"><img src="/images/upm-2023.png" /></a>
</div>
<p>To my surprise, the poster promoting the University Programming Marathon has evolved to be a bit iconic.
From what I can dig up, it was first used in 2014.</p>
</div>

<div class="captioned-poster">
<div class="poster">
    <a href="/images/imo-2006.png"><img src="/images/imo-2006.png" /></a>
</div>
<p>To my even bigger surprise, the IMO website still uses the design from 2006.</p>
</div>