---
title: Pizza as a Service 2.0
layout: post
permalink: /PizzaAsAService/
theme: beige
 
slides:
 - title: Pizza as a Service 2.0
   slide-data: Cloud Data Processing<br> Tarea 997<br> Julio Paredes<br>
 
     
 - title: Descripcion
   slide-data: Pizza as a Service es una analogía de la computación en la nube.<br><br>Representa cómo un sistema digital puede ofrecer servicios de forma remota, como si fuera una “pizza bajo demanda”.<br><br>El usuario solicita un servicio y este se entrega sin necesidad de infraestructura local.

     
 - title: Ventajas
   slide-data: • Acceso desde cualquier lugar<br>• Escalabilidad automática<br> • Menor costo de infraestructura<br> • Automatización de procesos<br> • Fácil mantenimiento y actualización

     
 - title: Desventajas
   slide-data: • Dependencia de internet<br>• Riesgos de seguridad y privacidad<br>• Posibles tiempos de latencia<br>• Menor control sobre la infraestructura<br>• Fallos del proveedor afectan el servicio

     
 - title: Casos de uso
   slide-data: • Aplicaciones web (SaaS)<br>• Plataformas de streaming<br>• Sistemas de pedidos en línea<br>• Almacenamiento en la nube<br>• Servicios empresariales digitales
 
     
 - title: Ejemplos
   slide-data: • Netflix (streaming como servicio)<br>• Google Drive (almacenamiento en la nube)<br>• AWS (infraestructura en la nube)<br>• Uber (servicio digital bajo demanda)<br>• Sistemas de delivery de comida
 

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
