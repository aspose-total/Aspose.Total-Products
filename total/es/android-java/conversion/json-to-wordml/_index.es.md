---
title: Convierta el formato JSON a WORDML en Android a través de Java
description: Analice JSON a WORDML en Java sin usar Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: WORDML
otherformats: CHM MOBI DOT DOTX EPUB DOCM PCL PS ODT WORD RTF FLATOPC DOC OTT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta el formato JSON a WORDML en aplicaciones de Android" h2="Analice JSON a WORDML dentro de las aplicaciones de Android sin usar Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede convertir JSON a WORDML en sus aplicaciones de Android en un proceso de dos pasos. En primer lugar, mediante el uso de la potente API de procesamiento de hojas de cálculo [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) puede analizar JSON a PDF. En el segundo paso, puede convertir PDF a WORDML mediante la API de procesamiento de textos [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/). Ambas API pertenecen a la familia de productos [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato JSON a WORDML en Android a través de Java" %}}
1. Cree un nuevo objeto [Libro de trabajo](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) y lea los datos JSON válidos del archivo
2. Importe el archivo JSON a la hoja de trabajo usando la clase [JsonUtility](https://reference.aspose.com/cells/java/com.aspose.cells/JsonUtility) y [Guardar](https://reference.aspose.com/cell/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) como PDF
3. Cargue el documento PDF utilizando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Guarde el documento en formato WORDML usando [Guardar](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) )) método
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total for Android via Java directamente desde [Maven](https://releases.aspose.com/total/java/)

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-doc.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Establecer diseño y convertir formato JSON a WORDML en Android a través de Java" %}}
Además, la API le permite establecer opciones de diseño para su formato JSON mientras analiza JSON a WORDML usando [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Le permite procesar Array como una tabla, ignorar nulos, ignorar el título de la matriz, ignorar el título del objeto, convertir cadenas en números o fechas, establecer el formato de fecha y número y establecer el estilo del título. Todas estas opciones le permiten presentar sus datos según sus necesidades. El siguiente fragmento de código le muestra cómo configurar las opciones de diseño.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "set-layout-and-parse-json-to-doc.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta el formato JSON a WORDML con marca de agua en Android a través de Java" %}}
Usando la API, también puede convertir JSON a WORDML con marca de agua. Para agregar una marca de agua a su documento WORDML, primero puede analizar el archivo JSON en PDF y agregarle una marca de agua. Para agregar una marca de agua, cargue el archivo PDF recién creado usando la clase [Document](https://reference.aspose.com/words/java/com.aspose.words/Document), cree una instancia de TextWatermarkOptions y configure sus propiedades, llame al método Watermark.setText y pase el texto y el objeto de la marca de agua de TextWatermarkOptions. Después de agregar la marca de agua, puede guardar el documento en WORDML.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "35ed6fd1fd3e1863f01e476f36f05625" "parse-json-to-word-with-watermark.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}