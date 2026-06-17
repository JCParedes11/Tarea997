---
title: Pizza as a Service 2.0
layout: post
permalink: /PizzaAsAService/
theme: beige
 
slides:
 - title: Pizza as a Service 2.0
   slide-data: Cloud Data Processing<br> Tarea #997<br> Julio Paredes<br>
 
     
- title: Descripción
    slide-data: |
      Pizza as a Service es una analogía de la computación en la nube.<br><br>
      Representa cómo un sistema digital puede ofrecer servicios de forma remota, como si fuera una “pizza bajo demanda”.<br><br>
      El usuario solicita un servicio y este se entrega sin necesidad de infraestructura local.

   
 - title: Slide 3
   slide-data: This is third slide

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
