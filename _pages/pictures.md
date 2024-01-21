---
title: "Wang Haiying Group - Pictures"
layout: piclay
excerpt: "Wang Haiying Group -- Pictures"
permalink: /pictures/
---

# Media

### Vedios

**December 2023**
<div style="position: relative; padding-bottom: 40%; height: 0; overflow: hidden;">
  <video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" controls>
    <source src="/images/media/vedios/December 2023.MOV" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
<br/>

**April 2023**
<div style="position: relative; padding-bottom: 40%; height: 0; overflow: hidden;">
  <video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" controls>
    <source src="/images/media/vedios/April 2023.MP4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
<br/>

**March 2023**
<div style="position: relative; padding-bottom: 40%; height: 0; overflow: hidden;">
  <video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" controls>
    <source src="/images/media/vedios/March 2023.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
<br/>

**January 2023**
<div style="position: relative; padding-bottom: 40%; height: 0; overflow: hidden;">
  <video style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;" controls>
    <source src="/images/media/vedios/January 2023.MP4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
<br/>

### Photos

#### Gallery

{% assign number_printed = 0 %}
{% for pic in site.data.pictures_WHY %}

{% assign even_odd = number_printed | modulo: 4 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-3 clearfix">
<img src="{{ site.url }}{{ site.baseurl }}/images/picpic/Gallery/{{ pic.image }}" class="img-responsive" width="95%" style="float: left" />
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd > 2 %}
</div>
{% endif %}


{% endfor %}

{% assign even_odd = number_printed | modulo: 4 %}
{% if even_odd == 1 %}
</div>
{% endif %}

{% if even_odd == 2 %}
</div>
{% endif %}

{% if even_odd == 3 %}
</div>
{% endif %}

<p> &nbsp; </p>
