---
lang: en
title: "People"
permalink: /people/

collection: people
entries_layout: grid
teaser_class: staff
sort_by: orden 



excerpt: "About ERPI"
header:
  overlay_image: /assets/images/about/erpi-travail.jpg
  image_description: "Equipe de Recherche sur les Processus Innovatifs"

last_modified_at: 2020-02-02
---

{% include toc icon="cog" title="People at ERPI" %}



## Professors

<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html 
    collection=page.collection 
    type=page.entries_layout 
    teaser_class=page.teaser_class 
    sort_by = 'orden'    
    role = "Prof" 
%}
</div>

<div style="width: 100%; clear: both; "></div>


## Assistant Professors

<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html 
    collection=page.collection 
    type=page.entries_layout 
    teaser_class=page.teaser_class    
    role = "MCF"
    sort_by = 'orden' 
%}
</div>

<div style="width: 100%; clear: both;"></div>


## Teaching and Research Assistants / Post Docs 


<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html  
    collection=page.collection  
    type=page.entries_layout 
    teaser_class=page.teaser_class   
    sort_by = 'orden' 
    role="IR" 
%}
</div>


<div style="width: 100%; clear: both;"></div>


## PhD Students

<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html  
    collection=page.collection  
    type=page.entries_layout 
    teaser_class=page.teaser_class   
    sort_by = 'orden' 
    role="PHD" 
%}
</div>


<div style="width: 100%; clear: both;"></div>

## Administrative and Technical Staff

<div class = "entries-{{ page.entries_layout }}">
{% include documents-collection.html  collection=page.collection  type=page.entries_layout  teaser_class = page.teaser_class  sort_by = "orden"  role= "Admin" %}


