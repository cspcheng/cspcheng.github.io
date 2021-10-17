---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
classes: wide
---

You can find my publications on the following systems.

<a href="{{ site.author.googlescholar }}"><i class="ai ai-fw ai-google-scholar"></i> Google Scholar</a>   
<a href="{{ site.author.dblp }}"><i class="ai ai-fw ai-dblp"></i> dblp</a>   
<a href="{{ site.author.orcid }}"><i class="ai ai-fw ai-orcid"></i> ORCID</a>    
<a href="https://publons.com/researcher/1438568/peng-cheng/"><i class="ai ai-fw ai-publons"></i> Publons</a>     



You can download my [own bibtex file](https://cspcheng.github.io/files/peng-publications.bib) which serves to generate the list below (which might take a few seconds to appear depending on your connection). Here is an [interactive publication list](https://bibbase.org/show?bib=https://cspcheng.github.io/files/peng-publications.bib&theme=bullets&authorFirst=1) built by [BIBBASE](https://bibbase.org/).


{% include my_publications.html %}



{% include base_path %}

<!-- {% capture written_year %}'None'{% endcapture %}
{% for post in site.publications reversed %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}

    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
​    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %} -->

