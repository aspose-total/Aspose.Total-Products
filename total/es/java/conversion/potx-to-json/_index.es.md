---
title: Convierta POTX a formato JSON a través de Java
description: Convierta el formato POTX a JSON a través de Java sin usar Microsoft Excel o PowerPoint
url_ignore: /es/java/conversion/potx-to-json/
family: total
platformtag: net
feature: conversion
informat: POTX
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta POTX a formato JSON a través de Java" h2="API de Java local para exportar POTX a JSON sin utilizar Microsoft<sup>&reg;</sup> Excel o PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Convertir POTX a formato JSON a través de [Aspose.Total for Java](https://products.aspose.com/total/java/) es un proceso simple de dos pasos. En el primer paso, puede exportar POTX a HTML usando [Aspose.Slides for Java](https://products.aspose.com/slides/java/). En segundo lugar, al usar [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puede convertir HTML a JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta POTX a formato JSON a través de Java" %}}
1. Abra el archivo POTX usando la clase [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
2. Convierta POTX a HTML usando [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) método
3. Cargue el documento HTML utilizando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el documento en formato JSON usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Usando la API, también puede abrir el documento protegido por contraseña. Si su documento POTX de entrada está protegido con contraseña, no puede convertirlo al formato JSON sin usar la contraseña. La API le permite abrir el documento cifrado pasando la contraseña correcta en un objeto LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta POTX protegido a formato JSON a través de Java" %}}
Mientras convierte POTX a JSON, también puede establecer el rango en su formato JSON de salida. Para establecer el rango, puede abrir el HTML convertido usando la clase Workbook, crear un rango de datos para exportar usando el método Cells.createRange, llamar al método JsonUtility.exportRangeToJson con referencias de Range y ExportRangeToJsonOptions y escribir datos JSON de cadena en el archivo a través de Método BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
## Conversión de POTX a JSON

{{< blocks/products/pf/agp/feature-section >}}

La conversión de POTX a JSON transforma el contenido de las diapositivas en Notación de Objetos JavaScript estructurada, ideal para aplicaciones web, paneles de control y procesamiento de datos impulsado por API.

{{% blocks/products/pf/agp/feature-section-col title="Casos de uso clave" %}}

* Exportar tablas y gráficos de presentación para paneles de control web.
* Convertir diapositivas en JSON para la ingestión de datos de IA o aprendizaje automático.
* Preparar herramientas de informes interactivos a partir de datos de presentación.
* Compartir contenido basado en diapositivas con aplicaciones web y plataformas SaaS.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Escenarios de automatización" %}}

* Conversión en lote de JSON para canalizaciones de análisis e informes.
* Integración con sistemas impulsados por API para el consumo de datos de diapositivas en tiempo real.
* Conversión activada para paneles web o móviles dinámicos.
* Extracción automatizada del contenido de las diapositivas en JSON estructurado para su procesamiento.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}