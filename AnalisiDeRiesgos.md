
# Incidentes de seguridad
## Unidad 1: Principios generales de la ciberseguridad
**Ciclo de Especialización de FP en Ciberseguridad en Entornos de las Tecnologías de la Información**

![](assets/AnalisisRiesgos.png "Análisis de Riesgos")

---

# ANÁLISIS DE RIESGOS

## Índice

[**Introducción**](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#introducci%C3%B3n)

[**1. Alcance del análisis**](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#1-alcance-del-an%C3%A1lisis)

[**2. Identificación de los activos**](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#2-identificaci%C3%B3n-de-los-activos)

[**3. Amenazas que pueden afectar a los activos**](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#3-amenazas-que-pueden-afectar-a-los-activos)

[**4. Identificar vulnerabilidades y salvaguardas**](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#4-identificar-vulnerabilidades-y-salvaguardas-4-identificar-vulnerabilidades-y-salvaguardas)

[4.1. Identificación de salvaguardas (Medidas y controles de seguridad)](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#41-identificaci%C3%B3n-de-salvaguardas-medidas-y-controles-de-seguridad)

[4.2. Vulnerabilidades/Debilidades](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#42-vulnerabilidadesdebilidades)

[**5. Evaluación y cálculo del riesgo**](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#5-evaluaci%C3%B3n-y-c%C3%A1lculo-del-riesgo)

[**6. Medidas complementarias que permitan materializar la protección de los activos.**](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#6-medidas-complementarias-que-permitan-materializar-la-protecci%C3%B3n-de-los-activos)

[**7. Conclusión**](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#7-conclusi%C3%B3n)

[**8. Bibliografía/Webgrafía**](https://github.com/IES-Rafael-Alberti/2425-u1-1-1-analisisderiesgos-grupo5/blob/master/AnalisiDeRiesgos.md#8-bibliograf%C3%ADawebgraf%C3%ADa)


---


## Introducción

- **Grupo e integrantes:**

**Grupo 5 \- G5**

* **Sergio González:** introducción, alcance del análisis, identificación de los activos y amenazas que pueden afectar a los activos, conclusión y bibliografía.
* **Iván Paúl:** introducción, alcance del análisis, identificación de los activos y amenazas que pueden afectar a los activos, conclusión y bibliografía.
* **Javier Calvillo:** identificar vulnerabilidades y salvaguardas (medidas y controles de seguridad), vulnerabilidades/debilidades, conclusión y bibliografía.
* **Manuel Pérez:** evaluación y cálculo del riesgo, medidas complementarias que permitan materializar la protección de los activos, conclusión y bibliografía.

- **Presentación del ejercicio**

Este trabajo analiza los riesgos de una empresa dedicada a la asesoría de autónomos y pymes, con el fin de identificar activos críticos, amenazas y vulnerabilidades, y proponer medidas para reducir los riesgos.

- **Contexto de la empresa**

La empresa ofrece servicios contables, fiscales, laborales y de gestión a autónomos y pymes. Cuenta con 150 empleados distribuidos en dos sedes, donde son habituales las visitas de clientes y proveedores. Dispone de servidores, redes, dispositivos móviles, servicios en la nube y una web con tienda online. Actualmente se encuentra en un proceso de transformación digital y de mejora en materia de seguridad.

- **Objetivos de la empresa**

Ofrecer asesoría integral a autónomos y pymes, modernizando sus servicios mediante la digitalización. Busca reforzar su presencia online y garantizar la seguridad de la información, evitando incidentes que afecten a su actividad y asegurando la continuidad del negocio.

- **Departamentos**

La empresa está organizada en los siguientes departamentos, cada uno con su propio responsable: **Facturación y Ventas**, **Compras**, **Comunicación y Redes Sociales** (RRSS), **Tecnologías de la Información y Comunicaciones** (TIC), **Recursos Humanos** (RRHH), **Delivery**, **Mantenimiento**, **Legal** y el **Consejo de Administración**.

- **Instalaciones y Sedes**

La empresa cuenta con **dos sedes**: una **principal**, que ocupa un edificio completo y alberga los departamentos de dirección, administración, TIC y recursos humanos; y una **secundaria**, situada en la segunda planta de un edificio compartido, donde trabajan los equipos de ventas, comunicación y atención al cliente. Ambas disponen de puestos equipados con ordenadores, impresoras, teléfonos, portátiles, tabletas y dispositivos de almacenamiento externo.

- **Servicios TIC**

La empresa dispone de diversos servicios tecnológicos, entre ellos servidores internos para correo, archivos y aplicaciones; red interna y WIFI; acceso a Internet y routers; servicios en la nube para almacenamiento y respaldo; además de una página web y tienda online alojadas externamente. También cuenta con equipos de usuario (ordenadores, portátiles, móviles e impresoras) y sistemas de copia de seguridad con almacenamiento externo.

- **Calendario de realización y seguimiento, y revisión del análisis**

* **Viernes (24/10/2025):** desarrollo de los apartados 1\. Introducción y 2\. Alcance del análisis, incluyendo la revisión de toda la información proporcionada por el profesor para comprender el caso.

* **Sábado (25/10/2025):** desarrollo de los apartados 3\. Identificación de los activos, 4\. Amenazas que pueden afectar a los activos, 5\. Identificación de vulnerabilidades y salvaguardas, incluyendo 5.1. Salvaguardas y 5.2. Vulnerabilidades/Debilidades.

* **Domingo (26/10/2025):** desarrollo de los apartados 6\. Evaluación y cálculo del riesgo, 7\. Medidas complementarias para proteger los activos, 8\. Conclusión, revisión final del informe y redacción completa.

## 1. Alcance del análisis
El análisis de riesgos forma parte del Plan Director de Seguridad (PDS) de la empresa y tiene como objetivo identificar y evaluar los riesgos que pueden afectar a los activos tecnológicos y a la información que se gestiona.

En este caso, el estudio se centra en los servicios y sistemas del Departamento de Informática (TIC), encargado de administrar los servidores, redes, equipos, copias de seguridad y aplicaciones críticas como CRM y ERP. Cualquier problema en este departamento podría impactar directamente en la continuidad del negocio y en la disponibilidad de los servicios.

El análisis también tiene en cuenta la comunicación del área TIC con otros departamentos, especialmente aquellos que manejan información sensible, como Ventas, RRHH o Legal, además de la dependencia de servicios externos como la página web y el almacenamiento en la nube.

El alcance incluye los sistemas internos de las dos sedes, los recursos digitales utilizados por los empleados y los servicios en la nube, quedando fuera los aspectos de seguridad física, que son gestionados por empresas externas.

## 2. Identificación de los activos

Una vez definido el alcance, se identifican los activos más relevantes del Departamento de Informática (TIC) y de los servicios tecnológicos de la empresa. Estos activos son esenciales para el funcionamiento diario, la gestión de la información y la continuidad de la actividad.

Para mantener un control adecuado, se ha elaborado un inventario de activos que recoge los elementos más importantes, como servidores, equipos, aplicaciones, redes, sistemas en la nube y servicios externos. En él se detalla su descripción, responsable, tipo, ubicación y si es crítico.

El inventario completo se encuentra disponible en el archivo Excel, llamado **plan\_director\_de\_seguridad\_inventario\_activos.xls**, adjunto a esta entrega.

## 3. Amenazas que pueden afectar a los activos

Las principales amenazas que pueden afectar a los activos de la empresa provienen de factores físicos, técnicos y humanos. Estas pueden comprometer la confidencialidad, integridad o disponibilidad de la información y de los sistemas, afectando directamente al funcionamiento diario de la organización.

Entre las más destacadas se encuentran:

* **Físicas o ambientales:** incendio, daños por agua, cortes eléctricos o desastres naturales.

* **Técnicas:** fallos de hardware o software, errores de mantenimiento, caídas del sistema o ataques de denegación de servicio.

* **Humanas:** errores de usuarios o administradores, pérdida o robo de dispositivos, abuso de privilegios o accesos no autorizados.

* **De información:** fuga, alteración o destrucción de datos, introducción de información falsa, malware o técnicas de ingeniería social.

Estas amenazas pueden afectar tanto a los sistemas internos como a los servicios externos, provocando pérdida de información, interrupciones del servicio o impactos negativos en la empresa.

## 4. Identificar vulnerabilidades y salvaguardas {#4.-identificar-vulnerabilidades-y-salvaguardas}

El análisis de riesgos permite conocer el nivel actual de protección de la empresa, identificar debilidades y establecer una base para la mejora continua dentro del Plan Director de Seguridad.

### 4.1. Identificación de salvaguardas (Medidas y controles de seguridad)

La empresa dispone de algunas medidas básicas de seguridad, entre ellas:

* Copias de seguridad gestionadas por el personal TIC, con procedimientos documentados.

* Antivirus corporativo administrado por una empresa subcontratada.

* Firewall perimetral que segmenta la red interna por departamentos.

* Cumplimiento del RGPD garantizado mediante una consultoría externa.

* Controles físicos de acceso gestionados por empresas de seguridad.

Aunque estas salvaguardas ofrecen una base de protección, necesitan mayor formalización, revisión periódica y aprobación directiva para asegurar una gestión eficaz.

### 4.2. Vulnerabilidades/Debilidades

Entre las principales debilidades detectadas se encuentran:

* Falta de políticas de seguridad formalizadas y aprobadas por la dirección.  
* Escasa formación del personal en materia de ciberseguridad.  
* Gestión externa de la web y tienda online sin control interno.  
* Dependencia de proveedores sin auditorías de seguridad.  
* Copias de seguridad almacenadas localmente, con riesgo ante siniestros.  
* Ausencia de un plan de respuesta ante incidentes.

Estas vulnerabilidades evidencian la necesidad de implantar un **Sistema de Gestión de la Seguridad de la Información (SGSI)** que mejore la protección de los activos y garantice la continuidad del negocio.

## 5. Evaluación y cálculo del riesgo

Una vez identificados los activos, las amenazas y las vulnerabilidades, se procede a la **evaluación de los riesgos** para determinar la probabilidad de que un incidente ocurra y el impacto que tendría sobre la empresa.  
El análisis se ha realizado siguiendo una metodología cualitativa basada en la guía del **INCIBE** y el **método MAGERIT**, considerando los tres pilares fundamentales de la seguridad de la información: **confidencialidad, integridad y disponibilidad (CID)**.

1. ## **Metodología**

Cada riesgo se valora asignando una puntuación cualitativa a:

* **Probabilidad (P):** posibilidad de que ocurra una amenaza (Baja, Media, Alta).  
* **Impacto (I):** consecuencias sobre la organización si la amenaza se materializa (Bajo, Medio, Alto).

El **nivel de riesgo (R)** se calcula mediante la relación:  
 **R \= P × I**, obteniendo una clasificación final:

* **Riesgo Bajo:** se acepta con medidas de control básicas.  
* **Riesgo Medio:** requiere seguimiento y controles preventivos.  
* **Riesgo Alto:** requiere medidas urgentes de mitigación y plan de acción.

## 6. Medidas complementarias que permitan materializar la protección de los activos.

A partir de la evaluación de riesgos, se proponen las siguientes **medidas complementarias de seguridad**, orientadas a reforzar la protección de los activos, reducir la probabilidad de incidentes y mejorar la madurez del sistema de seguridad.

#### **6.1. Medidas organizativas**

* **Definir una Política de Seguridad de la Información (PSI):** aprobada por la dirección, estableciendo roles, responsabilidades y normas de uso de los recursos TIC.  
* **Crear un Comité de Seguridad:** liderado por el responsable de seguridad y representantes de los principales departamentos.  
* **Desarrollar un Plan de Continuidad del Negocio (BCP):** que contemple procedimientos ante incidentes graves y copias de respaldo fuera de las instalaciones.  
* **Implantar un sistema de gestión de seguridad (SGSI)** basado en ISO 27001, para sistematizar controles y auditorías.

#### **6.2. Medidas técnicas**

* **Actualizar y centralizar el sistema antivirus** bajo supervisión del área TIC, asegurando su aprobación formal y revisión periódica.  
* **Implantar un sistema de gestión de parches** para mantener actualizados todos los equipos, servidores y aplicaciones.  
* **Configurar copias de seguridad automáticas** y verificadas regularmente, incluyendo almacenamiento en la nube cifrada y recuperación de prueba.  
* **Revisar la configuración del firewall** y segmentar adecuadamente las redes, restringiendo accesos por departamentos.  
* **Implementar autenticación multifactor (MFA)** para accesos remotos y servicios críticos (correo, ERP, CRM, nube).  
* **Cifrado de dispositivos móviles y portátiles** para proteger la información en caso de pérdida o robo.  
* **Monitorización continua y detección de intrusiones (IDS/IPS)** en la red interna.

## 7. Conclusión

Con este trabajo aprendimos lo importante que es cuidar lo más valioso de la empresa, como los datos y los sistemas que usamos todos los días. Nos dimos cuenta de que no solo basta con tener medidas de seguridad, sino que también hay que organizarlas, enseñar al personal y tener un plan por si algo falla.

En resumen, proteger la información y los recursos ayuda a que la empresa siga funcionando sin problemas y de manera más segura.

## 8. Bibliografía/Webgrafía

- **INCIBE. Guía de gestión de riesgos de ciberseguridad (PDF). Disponible en:** [https://www.incibe.es/sites/default/files/contenidos/guias/doc/guia\_ciberseguridad\_gestion\_riesgos\_metad.pdf](https://www.incibe.es/sites/default/files/contenidos/guias/doc/guia_ciberseguridad_gestion_riesgos_metad.pdf)

- **Revilofe. (2023). Análisis de riesgos – Introducción y fases. Recuperado de** [https://revilofe.github.io/section2/u01/teoria/IS-U1.2.2.-AnalisiDeRiesgos/](https://revilofe.github.io/section2/u01/teoria/IS-U1.2.2.-AnalisiDeRiesgos/)

- **INCIBE – Guía de Ciberseguridad para Empresas**

* Instituto Nacional de Ciberseguridad de España. "Análisis de riesgos en 6 pasos". Recuperado de: [https://www.incibe.es/empresas/blog/analisis-riesgos-pasos-sencillo](https://www.incibe.es/empresas/blog/analisis-riesgos-pasos-sencillo)  
- **INCIBE – Metodologías de Análisis de Riesgos**  
* Instituto Nacional de Ciberseguridad de España. "Metodologías de Análisis de Riesgos". Recuperado de: [https://www.incibe.es/sites/default/files/contenidos/dosieres/plan-director-seguridad/plan\_director\_de\_seguridad\_metodologias\_analisis\_de\_riesgos.pdf](https://www.incibe.es/sites/default/files/contenidos/dosieres/plan-director-seguridad/plan_director_de_seguridad_metodologias_analisis_de_riesgos.pdf)  
    
- **NQA – Guía de Implantación de ISO 27001:2022**

* NQA. "ISO 27001:2022 – Guía de Implantación". Recuperado de: [https://www.nqa.com/medialibraries/NQA/NQA-Media-Library/PDFs/Spanish%20QRFs%20and%20PDFs/NQA-ISO-27001-Guia-de-implantacion.pdf](https://www.nqa.com/medialibraries/NQA/NQA-Media-Library/PDFs/Spanish%20QRFs%20and%20PDFs/NQA-ISO-27001-Guia-de-implantacion.pdf)  
    
- **Wikipedia – ISO/IEC 27001**

* Wikipedia. "ISO/IEC 27001". Recuperado de: [https://es.wikipedia.org/wiki/ISO/IEC\_27001](https://es.wikipedia.org/wiki/ISO/IEC_27001)  
  
