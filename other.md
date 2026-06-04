---
layout: page
title: Other
---

{% assign posters = site.data.posters %}

# Other

I have a design ~~problem~~ hobby.

## Posters

{% for poster in posters %}
<div class="poster">
    <a href="/images/{{ poster.file }}"><img src="/images/{{ poster.file }}" alt="{{ poster.name }} poster" loading="lazy" /></a>
</div>
{% endfor %}
<div class="clr"></div>

## Prehistory

<div class="captioned-poster">
<div class="poster">
    <a href="/images/upm-2023.png"><img src="/images/upm-2023.png" alt="University Programming Marathon poster (first used 2014)" loading="lazy" /></a>
</div>
<p>To my surprise, the poster promoting the University Programming Marathon has evolved to be a bit iconic, to the extent that they don't want to change it (yet).
From what I can dig up, it was first used in 2014.</p>
</div>

<div class="captioned-poster">
<div class="poster">
    <a href="/images/imo-2006.png"><img src="/images/imo-2006.png" alt="International Mathematical Olympiad 2006 poster" loading="lazy" /></a>
</div>
<p>To my even bigger surprise, the IMO website still uses the design from 2006.</p>
</div>