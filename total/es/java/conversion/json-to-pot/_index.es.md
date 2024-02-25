---
title: Convierta el formato JSON a POT a través de Java
description: Analice JSON a POT en Java sin usar Microsoft PowerPoint
url_ignore: /es/java/conversion/json-to-pot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: POT
otherformats: POWERPOINT OTP PPTM POTX POTM PPS POT PPSM PPSX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el formato JSON a POT a través de Java" h2="API de Java para analizar el formato JSON en POT sin utilizar Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/), puede convertir el formato JSON a POT dentro de cualquier aplicación Java en dos simples pasos. En primer lugar, al usar [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puede analizar JSON a PPTX. Después de eso, usando [Aspose.Slides for Java](https://products.aspose.com/slides/java/), puede convertir PPTX a POT.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato JSON a POT a través de Java" %}}
1. Cree un nuevo objeto [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) y abra el archivo JSON
2. Guarde JSON como PPTX usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
3. Cargue el documento PPTX usando la clase [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Guarde el documento en formato POT usando el método [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-)
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Además, la API le permite analizar JSON a POT con opciones de diseño específicas. Para especificar las opciones de diseño, puede usar la clase [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Le permite procesar una matriz como una tabla, ignorar nulos, ignorar el título de la matriz, ignorar el título del objeto, convertir una cadena en un número o fecha, establecer el formato de fecha y número y establecer el estilo del título. Todas estas opciones le permiten presentar sus datos según sus necesidades. El siguiente fragmento de código le muestra cómo configurar las opciones de diseño.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Establezca el diseño y convierta el formato JSON a POT a través de Java" %}}
Usando la API, también puede convertir JSON a POT con marca de agua. Para agregar una marca de agua a su documento POT, primero puede analizar JSON a PPTX y agregarle una marca de agua. Para agregar una marca de agua, cargue el archivo PPTX recién creado usando la clase [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), recorra todas las diapositivas, agregue texto usando addTextFrame, configure todas las opciones relevantes como color, tipo de relleno y más y puede guardar el documento en POT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}