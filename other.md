---
layout: page
title: Katja Berčič | Other
---

{% assign posters = site.data.posters %}

# Other

I have a design ~~problem~~ hobby.

## Recent posters

{% for poster in posters %}
<div class="poster">
    <a href="/images/{{ poster.file }}"><img src="/images/{{ poster.file }}" /></a>
</div>
{% endfor %}
<div class="clr"></div>

## UPM

<div class="captioned-poster">
<div class="poster">
    <a href="/images/upm-2023.png"><img src="/images/upm-2023.png" /></a>
</div>
<p>To my surprise, the poster promoting the University Programming Marathon has evolved to be a bit iconic.
From what I can dig up, it was first used in 2014.</p>
</div>