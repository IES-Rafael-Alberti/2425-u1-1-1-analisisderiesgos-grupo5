
# Incidentes de seguridad
## Unidad 1: Principios generales de la ciberseguridad
**Ciclo de Especialización de FP en Ciberseguridad en Entornos de las Tecnologías de la Información**

![](assets/AnalisisRiesgos.png "Análisis de Riesgos")

---

# ANÁLISIS DE RIESGOS

## Índice

[**Introducción**](#0.-introducción)

[**Alcance del análisis**](#0.-introducción)

[**2. Identificación de los activos**](#2.-identificación-de-los-activos)

[**3. Amenazas que pueden afectar a los activos**](#3.-amenazas-que-pueden-afectar-a-los-activos)

[**4. Identificar vulnerabilidades y salvaguardas**](#4.-identificar-vulnerabilidades-y-salvaguardas)

[4.1. Identificación de salvaguardas (Medidas y controles de seguridad)](#4.1-identificación-de-salvaguardas-\(medidas-y-controles-de-seguridad\))

[4.2. Vulnerabilidades/Debilidades](#4.2-vulnerabilidades/debilidades)

[**5. Evaluación y cálculo del riesgo**](#5.-evaluación-y-cálculo-del-riesgo)

[**6. Medidas complementarias que permitan materializar la protección de los activos.**](#6.-medidas-complementarias-que-permitan-materializar-la-protección-de-los-activos.)

[**7. Conclusión**](#7.-conclusión)

[**8. Bibliografía/Webgrafía**](#8.-bibliografía/webgrafía)


---


## Introducción {#0.-introducción}

- **Grupo e integrantes:**

**Grupo 5 \- G5**

* **Sergio González:**   
* **Iván Paúl:**   
* **Javier Calvillo:**   
* **Manuel Pérez:** 

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

## 1. Alcance del análisis  {#1.-alcance-del-análisis}
Estrategía empresarial de la empresa, como afecta a las actividades comerciales.   
Departamento o área de la empresa que se va a analizar.

## 2. Identificación de los activos  {#2.-identificación-de-los-activos}

Una vez definido el alcance, se identifican los activos más relevantes del Departamento de Informática (TIC) y de los servicios tecnológicos de la empresa. Estos activos son esenciales para el funcionamiento diario, la gestión de la información y la continuidad de la actividad.

Para mantener un control adecuado, se ha elaborado un inventario de activos que recoge los elementos más importantes, como servidores, equipos, aplicaciones, redes, sistemas en la nube y servicios externos. En él se detalla su descripción, responsable, tipo, ubicación y si es crítico.

El inventario completo se encuentra disponible en el archivo Excel, llamado **plan\_director\_de\_seguridad\_inventario\_activos.xls**, adjunto a esta entrega.

## 3. Amenazas que pueden afectar a los activos {#3.-amenazas-que-pueden-afectar-a-los-activos}

Las principales amenazas que pueden afectar a los activos de la empresa provienen de factores físicos, técnicos y humanos. Estas pueden comprometer la confidencialidad, integridad o disponibilidad de la información y de los sistemas, afectando directamente al funcionamiento diario de la organización.

Entre las más destacadas se encuentran:

* **Físicas o ambientales:** incendio, daños por agua, cortes eléctricos o desastres naturales.

* **Técnicas:** fallos de hardware o software, errores de mantenimiento, caídas del sistema o ataques de denegación de servicio.

* **Humanas:** errores de usuarios o administradores, pérdida o robo de dispositivos, abuso de privilegios o accesos no autorizados.

* **De información:** fuga, alteración o destrucción de datos, introducción de información falsa, malware o técnicas de ingeniería social.

Estas amenazas pueden afectar tanto a los sistemas internos como a los servicios externos, provocando pérdida de información, interrupciones del servicio o impactos negativos en la empresa.

## 4. Identificar vulnerabilidades y salvaguardas {#4.-identificar-vulnerabilidades-y-salvaguardas}



### 4.1. Identificación de salvaguardas (Medidas y controles de seguridad)  {#4.1-identificación-de-salvaguardas-(medidas-y-controles-de-seguridad)}



### 4.2. Vulnerabilidades/Debilidades {#4.2-vulnerabilidades/debilidades}



## 5. Evaluación y cálculo del riesgo {#5.-evaluación-y-cálculo-del-riesgo}

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

## 6. Medidas complementarias que permitan materializar la protección de los activos. {#6.-medidas-complementarias-que-permitan-materializar-la-protección-de-los-activos.}

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

## 7. Conclusión {#7.-conclusión}

## 8. Bibliografía/Webgrafía {#8.-bibliografía/webgrafía}
