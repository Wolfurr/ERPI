---
lang: fr
title: "Membres"
permalink: /fr/people/

collection: people
entries_layout: grid
teaser_class: staff
sort_by: orden

excerpt: "Les membre de l'équipe"
header:
  overlay_image: /assets/images/banner/bannerequipe.jpg
  image_description: "Equipe de Recherche sur les Processus Innovatifs"

---


{% include toc icon="cog" title="People at ERPI" %}



## Corps enseignant 

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


## Assistants professeurs

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


## Assistants enseignants chercheurs / Post Docs 


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


## Doctorants

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

## Personnel administratif et technique

<div class = "entries-{{ page.entries_layout }}">
{% include documents-collection.html  
    collection=page.collection
    type=page.entries_layout  
    teaser_class = page.teaser_class  
    sort_by = "orden"  
    role= "Admin" %}

