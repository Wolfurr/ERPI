---
lang: fr
title: "Projects ERPI"
permalink: /fr/projects/
layout: single
class: wide
#layout: collection
collection: projects
entries_layout: grid


excerpt: "Projets du laboratoire"
header:
  overlay_image: /assets/images/publications/articles.jpg
  image_description: "Equipe de Recherche sur les Processus Innovatifs"

sidebar:
  nav: "projects"

gallery:
  - image_path: /assets/images/projects/teasers/fr/1.jpg
    alt: "ERPI Innovation metrology"
    url: /fr/projects/#innovation-metrology
  - image_path: /assets/images/projects/teasers/fr/2.jpg
    alt: "ERPI Prospective"        
    url: /fr/projects/#prospective--weak-signals      
  - image_path: /assets/images/projects/teasers/fr/3.jpg
    alt: "ERPI Design"        
    url: /fr/projects/#design-support-in-front-end      
  - image_path: /assets/images/projects/teasers/fr/4.jpg
    alt: "ERPI Acceptability"        
    url: /fr/projects/#acceptability   

last_modified_at: 2019-10-16
---


{% include gallery  layout="four" %}

## Métrologie de l'innovation

<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout    
    Research-field = "Metrology"
%}
</div>
<div style="width: 100%; clear: both; "></div>

## Prospective et signaux faibles



<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout    
    Research-field = "Prospective"
%}
</div>
<div style="width: 100%; clear: both; "></div>

## Aide à la conception en phase amont

<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout    
    Research-field = "Design"
%}
</div>
<div style="width: 100%; clear: both; "></div>

## Acceptabilité

<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout
    Research-field = "Acceptability"
%}
</div>
