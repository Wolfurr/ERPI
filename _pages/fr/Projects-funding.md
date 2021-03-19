---
title: "Projets à l'ERPI"
permalink: fr/projects/funding/
layout: single
classes: wide
#layout: collection
collection: projects
entries_layout: grid


excerpt: "Projets de recherches à l'ERPI"
header:
  overlay_image: /assets/images/banner/bannerprojet2.jpg
  image_description: "Equipe de Recherche sur les Processus Innovatifs"

sidebar:
  nav: "projects"

gallery:
  - image_path: /assets/images/projects/teasers/1.jpg
    alt: "ERPI Innovation metrology"
    url: /projects/#innovation-metrology
  - image_path: /assets/images/projects/teasers/2.jpg
    alt: "ERPI Prospective"        
    url: /projects/#prospective--weak-signals      
  - image_path: /assets/images/projects/teasers/3.jpg
    alt: "ERPI Design"        
    url: /projects/#design-support-in-front-end      
  - image_path: /assets/images/projects/teasers/4.jpg
    alt: "ERPI Acceptability"        
    url: /projects/#acceptability     


---



##  Européens  <img class="emoji" title=":EU:" alt=":EU:" src="/assets/images/projects/inedit/EU-logo.png" height="20" width="20">


<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout        
    Funding = "EU"
%}
</div>
<div style="width: 100%; clear: both; "></div>



## Nationaux :fr:

<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout        
    Funding = "FR"
%}
</div>
<div style="width: 100%; clear: both; "></div>

## Regionaux

<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout        
    Funding = "Lorraine"
%}
</div>
<div style="width: 100%; clear: both; "></div>

## Universitaires
<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout        
    Funding = "UL"
%}
</div>
<div style="width: 100%; clear: both; "></div>



## Ville
<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html
    collection=page.collection
    type=page.entries_layout        
    Funding = "Nancy"
%}
</div>
<div style="width: 100%; clear: both; "></div>


