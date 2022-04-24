---
title: Convierta el formato JSON a DOTX a través de Java
description: Analice JSON a DOTX en Java sin usar Microsoft Word
url: /es/java/conversion/json-to-dotx/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: DOTX
otherformats: DOCM PS OTT WORD PCL RTF DOT FLATOPC EPUB ODT DOTX DOC WORDML MOBI
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta el formato JSON a DOTX a través de Java" h2="API Java local para analizar JSON a DOTX sin usar Microsoft<sup>&reg;</sup> Word" >}}
{{% blocks/products/pf/feature-page-summary %}}
Al usar [Aspose.Total for Java](https://products.aspose.com/total/java/) puede convertir JSON a DOTX en sus aplicaciones Java en un proceso de dos pasos. En primer lugar, al usar [Aspose.Cells for Java](https://products.aspose.com/cells/java/) puede analizar JSON a PDF. En el segundo paso, puede convertir PDF a DOTX utilizando la API de procesamiento de textos [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato JSON a DOTX a través de Java" %}}
1. Cree un nuevo objeto [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) y lea los datos JSON válidos del archivo.
2. Importe el archivo JSON a la hoja de trabajo usando la clase [JsonUtility](https://apireference.aspose.com/cells/java/com.aspose.cells/JsonUtility) y [Guardar](https://apireference.aspose.com/ cell/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) como PDF
3. Cargue el documento PDF usando la clase [Documento](https://apireference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato DOTX mediante [Guardar](https://apireference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Además, la API le permite establecer opciones de diseño para su JSON mientras analiza JSON en DOTX mediante [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Le permite procesar Array como una tabla, ignorar nulos, ignorar el título de la matriz, ignorar el título del objeto, convertir cadenas en números o fechas, establecer el formato de fecha y número y establecer el estilo del título. Todas estas opciones le permiten presentar sus datos según sus necesidades. El siguiente fragmento de código le muestra cómo configurar las opciones de diseño.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Establecer diseño y convertir formato JSON a DOTX a través de Java" %}}
Usando la API, también puede analizar JSON a DOTX con marca de agua. Para agregar una marca de agua a su documento DOTX, primero puede convertir el archivo JSON a PDF y agregarle una marca de agua. Para agregar una marca de agua, cargue el archivo PDF recién creado usando la clase [Document](https://apireference.aspose.com/words/java/com.aspose.words/Document), cree una instancia de TextWatermarkOptions y configure sus propiedades, llame al método Watermark.setText y pase el texto y el objeto de la marca de agua de TextWatermarkOptions. Después de agregar la marca de agua, puede guardar el documento en DOTX. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras opciones de conversión" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-flatopc/" name="JSON Para FLAParaPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-docm/" name="JSON Para DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-word/" name="JSON Para WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-wordml/" name="JSON Para WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-odt/" name="JSON Para ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-rtf/" name="JSON Para RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-doc/" name="JSON Para DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-mobi/" name="JSON Para MOBI" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-ott/" name="JSON Para OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-dotx/" name="JSON Para DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-pcl/" name="JSON Para PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-dot/" name="JSON Para DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-epub/" name="JSON Para EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/net/conversion/json-to-ps/" name="JSON Para PS" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}