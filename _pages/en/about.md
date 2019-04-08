---
lang: en
layout: single
title: "About ERPI"
permalink: /about/

collection: people
entries_layout: grid
teaser_class: staff
sort_by: orden 

excerpt: "About ERPI"
header:
  overlay_image: /assets/images/about/erpi-travail.jpg
  overlay_filter: 0.1
  show_overlay_excerpt: true 
  image_description: "Equipe de Recherche sur les Processus Innovatifs"

sidebar:
  nav: ""

intro:
  - excerpt: "**A multidisciplinary research team on innovation processess research**"

last_modified_at: 2019-04-08
---


{% include feature_row id="intro" type="center" %}


## Background

The **ERPI (Research team on innovation process)** is one of the [University of Lorraine](http://univ-lorraine.fr) research labs. It is labeled as such by the French Ministry of Higher Education, Research and Innovation. ERPI is a founding member of the Jacques Villermaux Federation and linked to the EMPP scientifique pole. ERPI has an historical link with the [ENSGSI](http://ensgsi.univ-lorraine.fr) (Engineering School on Innovation). 

ERPI is a research team on Industrial Engineering specialized on the research of innovation processes management. Its activities concerns the methods, tools and knowledges allowing to optimise innovation projects management.

The scientific project of the ERPI deals with the Fuzzy Front End off innovation that is to say from idea generation to materialization (CAD, formulation ...). ERPI differs to other innovation research laboratories by considering the product as a "integrating system".   



## Research subjects

 Some topics of research are 
 - Innovation management
 - Use assessment
 - Innovation assessment




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

<div class="entries-{{ page.entries_layout }}">
{% include documents-collection.html  
    collection=page.collection  
    type=page.entries_layout 
    teaser_class=page.teaser_class   
    sort_by = 'orden' 
    role="Admin" 
%}



