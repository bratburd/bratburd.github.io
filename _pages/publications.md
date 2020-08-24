---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


[MG Chevrette, <b>JR Bratburd</b>, CR Currie, RM Stubbendieck (2019) "Experimental Microbiomes: Models Not to Scale" <i>mSystems</i>4 (4), e00175-19](https://msystems.asm.org/content/4/4/e00175-19)

[<b>JR Bratburd</b>, C Keller, E Vivas, E Gemperline, L Li, FE Rey, CR Currie. (2018) "Gut Microbial and Metabolic Responses to <i>Salmonella enterica </i>Serovar Typhimurium and <i>Candida albicans</i>" <i>mBio</i> (6), e02032-18](https://mbio.asm.org/content/9/6/e02032-18)

[<b>JR Bratburd</b>, A Kowalkowski, GK Sidhu, K Crocker (2018) "Establishing a  forensic  science  commission  in Wisconsin" <i>Journal of Science Policy and Governance</i> 13 (1)](http://www.sciencepolicyjournal.org/uploads/5/4/3/4/5434385/bratburd.pdf)

[GK Blaisdell, S Zhang, <b>JR Bratburd</b>, KM Daane, ML Cooper, RPP Almeida. (2015) "Interactions within susceptible hosts drive establishment of genetically distinct variants of an insect-borne pathogen" <i>Journal of Economic Entomology</i> 108 (4), 1531-1539](https://academic.oup.com/jee/article-abstract/108/4/1531/2380269)



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
