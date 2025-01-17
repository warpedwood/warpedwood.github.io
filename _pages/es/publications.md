---
page_id: publications
layout: page
permalink: /publications/
title: publicaciones
sortby: true        # true: Sort by types | false: Sort by years
description: 
nav: true
nav_order: 1
---

{% include bib_search.liquid %}

<div class="publications">

{% bibliography -f papers --group_by type,year %}

</div>
