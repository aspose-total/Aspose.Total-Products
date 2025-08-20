---
title: Convierta DOCM a formato JSON a través de Java
description: Convierta el formato DOCM a JSON a través de Java sin usar Microsoft Word o Microsoft Excel
url_ignore: /es/java/conversion/docm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOCMM
outformat: JSON
otherformats: XLT XLTM FODS SXC XLAM XLS EXCEL ODS XLSM DIF XLSB XLTX TSV CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta DOCM a formato JSON a través de Java" h2="API de Java local para convertir DOCM a JSON sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Convertir DOCM a formato JSON a través de [Aspose.Total for Java](https://products.aspose.com/total/java/) es un proceso simple de dos pasos. Mediante el uso de la API de conversión y manipulación de documents rica en funciones [Aspose.Words for Java](https://products.aspose.com/words/java/), puede exportar DOCM a HTML. Después de eso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puede convertir HTML a JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta DOCM a formato JSON a través de Java" %}}
1. Abra el archivo DOCM usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
2. Convierta DOCM a HTML usando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) método
3. Cargue el document HTML utilizando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el document en formato JSON mediante [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Usando la API, también puede abrir el document protegido por contraseña. Si su ddocumentDOCM de entrada está protegido con contraseña, no puede convertirlo al formato JSON sin usar la contraseña. La API le permite abrir el dodocumentifrado pasando la contraseña correcta en un objeto LoadOptions. El siguiente ejemplo de código muestra cómo intentar abrir un docdocumentfrado con una contraseña:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta DOCM protegido a formato JSON a través de Java" %}}
Mientras convierte DOCM a JSON, también puede establecer el rango en su formato JSON de salida. Para establecer el rango, puede abrir el HTML convertido usando la clase Workbook, crear un rango de datos para exportar usando el método Cells.createRange, llamar al método JsonUtility.exportRangeToJson con referencias de Range y ExportRangeToJsonOptions y escribir datos JSON de cadena en el archivo a través de Método BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
## Conversión de **DOCM (Documentos habilitados para macros de Word)** a **JSON (Notación de Objetos JavaScript)**

Es vital para transformar el contenido de documentos estáticos, tablas y campos de formulario en **datos estructurados legibles por máquinas**. JSON es ligero, legible para humanos y ampliamente utilizado en **APIs, análisis, aplicaciones web y flujos de trabajo de automatización**. Al extraer datos de DOCM a JSON, las organizaciones pueden desbloquear la interoperabilidad en plataformas modernas, permitir integraciones más rápidas y asegurar que los datos estén listos para **procesamiento en tiempo real, validación y distribución escalable**.

## ✅ Casos de uso clave

- **Publicación de Datos de Documentos en APIs REST/GraphQL**
  Servir el contenido extraído de DOCM como JSON para su consumo directo en aplicaciones web y móviles.

- **Alimentación de Bases de Datos NoSQL y Data Lakes**
  Cargar datos estructurados derivados de DOCM en MongoDB, Elasticsearch o data lakes basados en la nube.

- **Potenciación de Paneles con Feeds JSON en Tiempo Real**
  Transmitir KPIs y métricas basadas en documentos en paneles de inteligencia empresarial y herramientas de monitoreo.

- **Validación de Entradas Contra Esquema JSON**
  Asegurar consistencia e integridad al alinear los datos de campo de DOCM con las reglas del esquema JSON.

- **Habilitación de CMS sin cabeza o Arquitecturas de Microservicios**
  Integrar contenido de DOCM en sistemas distribuidos primero en API donde JSON es la lingua franca.

## ⚙️ Escenarios de automatización

- **Extracción de DOCM a JSON con Mapeo de Campos**
  Definir mapeos para transformar tablas, encabezados y campos en objetos JSON estructurados.

- **Funciones sin servidor que Convierten y Emiten Eventos JSON**
  Disparar conversiones al cargar archivos, emitiendo cargas útiles JSON a sistemas basados en eventos.

- **Trabajos ETL que Normalizan Tipos y Claves**
  Estandarizar las exportaciones de DOCM en estructuras JSON consistentes para análisis posteriores.

- **Webhooks que Envían JSON a Sistemas Posteriores**
  Automatizar las exportaciones de DOCM a JSON que alimentan CRMs, herramientas ERP o aplicaciones de terceros.

- **Reglas de Gobernanza que Eliminan Macros e Información Personal Antes de la Exportación a JSON**
  Aplicar controles de cumplimiento para garantizar salidas JSON seguras y sanitizadas de archivos habilitados para macros.
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}