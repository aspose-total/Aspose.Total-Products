---
title: Convierta el formato JSON a DOT a través de Java
description: Analice JSON a DOT en Java sin usar Microsoft Word
url_ignore: /es/java/conversion/json-to-dot/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOT
otherformats: RTF FLATOPC ODT DOTX WORDML PCL DOC EPUB OTT WORD PS MOBI DOT DOCM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el formato JSON a DOT a través de Java" h2="API Java local para analizar JSON a DOT sin usar Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Al usar [Aspose.Total for Java](https://products.aspose.com/total/java/) puede convertir JSON a DOT en sus aplicaciones Java en un proceso de dos pasos. En primer lugar, al usar [Aspose.Cells for Java](https://products.aspose.com/cells/java/) puede analizar JSON a PDF. En el segundo paso, puede convertir PDF a DOT utilizando la API de procesamiento de textos [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato JSON a DOT a través de Java" %}}
1. Cree un nuevo objeto [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) y lea los datos JSON válidos del archivo.
2. Importe el archivo JSON a la hoja de trabajo usando la clase [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) y [save](https://reference.aspose.com/ cell/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) como PDF
3. Cargue el documento PDF usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato DOT mediante [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/)

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Además, la API le permite establecer opciones de diseño para su JSON mientras analiza JSON en DOT mediante [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Le permite procesar Array como una tabla, ignorar nulos, ignorar el título de la matriz, ignorar el título del objeto, convertir cadenas en números o fechas, establecer el formato de fecha y número y establecer el estilo del título. Todas estas opciones le permiten presentar sus datos según sus necesidades. El siguiente fragmento de código le muestra cómo configurar las opciones de diseño.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Establecer diseño y convertir formato JSON a DOT a través de Java" %}}
Usando la API, también puede analizar JSON a DOT con marca de agua. Para agregar una marca de agua a su documento DOT, primero puede convertir el archivo JSON a PDF y agregarle una marca de agua. Para agregar una marca de agua, cargue el archivo PDF recién creado usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), cree una instancia de TextWatermarkOptions y configure sus propiedades, llame al método Watermark.setText y pase el texto y el objeto de la marca de agua de TextWatermarkOptions. Después de agregar la marca de agua, puede guardar el documento en DOT. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}