---
title: TIC
layout: post
permalink: /InvestigacionTIC/
theme: league
 
slides:
 - title: TIC
   slide-data: Cloud Data Processing<br> Tarea 997<br> Julio Paredes<br>
 
     
 - title: 1.1 Solucion estratificada de problemas en TIC
   slide-data: Descripción:<br>Es un enfoque que divide sistemas complejos en capas o niveles organizados.<br><br>

     
 - title: Caracteristicas
   slide-data: • División por capas<br>• Modularidad<br>• Separación de responsabilidades<br>• Facilidad de mantenimiento

     
 - title: Casos de uso
   slide-data: • Arquitectura de software<br>• Redes de computadoras<br>• Sistemas empresariales<br><br>

     
 - title:Ejemplos
   slide-data: • Modelo OSI<br>• Arquitectura cliente-servidor<br>• Sistemas ERP

     
  - title: 1.1.a Virtualizacion por interpretacion pura
   slide-data: Descripción:<br>Ejecuta instrucciones del sistema invitado una por una mediante interpretación directa.<br><br>

     
 - title: Caracteristicas
   slide-data: • Interpretación instrucción por instrucción<br>• No compila código<br>• Alta compatibilidad<br>• Bajo rendimiento<br><br>

     
 - title: Casos de uso
   slide-data: • Emulación de sistemas antiguos<br>• Investigación de software<br>• Educación

     
 - title:Ejemplos
   slide-data: • Bochs<br>• QEMU (modo emulación)<br>• Emuladores de consolas

     
  - title: 1.1.b Virtualizacion por recopilacion dinamica
   slide-data: Descripción:<br>Traduce bloques de instrucciones a código nativo durante la ejecución.

     
 - title: Caracteristicas
   slide-data: • Traducción en tiempo real<br>• Mejora de rendimiento<br>• Reutilización de código compilado<br>• Optimización dinámica

     
 - title: Casos de uso 
   slide-data: • Máquinas virtuales modernas<br>• Emulación de videojuegos<br>• Compatibilidad entre arquitecturas

     
 - title:Ejemplos 
   slide-data: • QEMU (TCG)<br>• Rosetta 2<br>• DynamoRIO

     
  - title: 1.1.c Virtualizacion por hipervision (bare metal)
   slide-data: Descripción:<br> El hipervisor se ejecuta directamente sobre el hardware físico para crear máquinas virtuales.

     
 - title: Caracteristicas
   slide-data: • Acceso directo al hardware<br>• Alto rendimiento<br>• Aislamiento de sistemas<br>• Escalabilidad

     
 - title: Casos de uso
   slide-data: • Centros de datos<br>• Cloud computing<br>• Infraestructura empresarial

     
 - title:Ejemplos
   slide-data: • VMware ESXi<br>• Microsoft Hyper-V<br>• Xen

---

{% for slide in page.slides %}
                    
<section data-background="{% if slide.background %}{{slide.background}}{% else %}{{page.background}}{% endif %}"><h1>{{slide.title}}</h1>{{ slide.slide-data }}</section>
                    
{% endfor %}
