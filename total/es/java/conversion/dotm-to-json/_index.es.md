---
title: Convierta DOTM a formato JSON a través de Java
description: Convierta el formato DOTM a JSON a través de Java sin usar Microsoft Word o Microsoft Excel
url_ignore: /es/java/conversion/dotm-to-json/
family: total
platformtag: net
feature: conversion
informat: DOTM
outformat: JSON
otherformats: XLAM XLTX TSV FODS XLT DIF CSV EXCEL XLSB XLS XLSM XLTM SXC ODS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Convierta DOTM a formato JSON a través de Java" h2="API de Java local para convertir DOTM a JSON sin usar Microsoft<sup>&reg;</sup> Word o Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Convertir DOTM a formato JSON a través de [Aspose.Total for Java](https://products.aspose.com/total/java/) es un proceso simple de dos pasos. Mediante el uso de la API de conversión y manipulación de dotmumentos rica en funciones [Aspose.Words for Java](https://products.aspose.com/words/java/), puede exportar DOTM a HTML. Después de eso, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), puede convertir HTML a JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta DOTM a formato JSON a través de Java" %}}

1. Abra el archivo DOTM usando la clase [Dotmumento](https://reference.aspose.com/words/java/com.aspose.words/Dotmument)
2. Convierta DOTM a HTML usando [save](https://reference.aspose.com/words/java/com.aspose.words/Dotmument#save(java.lang.String,com.aspose.words.SaveOptions)) método
3. Cargue el dotmumento HTML utilizando la clase [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Guarde el dotmumento en formato JSON mediante [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.GuardarOpciones)) método

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Puede usar fácilmente Aspose.Total para Java directamente desde un proyecto basado en [Maven](https://releases.aspose.com/total/java/) e incluya bibliotecas en su pom.xml.

Alternativamente, puede obtener un archivo ZIP de [descargas](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversión" %}}
Usando la API, también puede abrir el dotmumento protegido por contraseña. Si su dotmumento DOTM de entrada está protegido con contraseña, no puede convertirlo al formato JSON sin usar la contraseña. La API le permite abrir el dotmumento cifrado pasando la contraseña correcta en un objeto LoadOptions. El siguiente ejemplo de código muestra cómo intentar abrir un dotmumento cifrado con una contraseña:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Convierta DOTM protegido a formato JSON a través de Java" %}}
Mientras convierte DOTM a JSON, también puede establecer el rango en su formato JSON de salida. Para establecer el rango, puede abrir el HTML convertido usando la clase Workbook, crear un rango de datos para exportar usando el método Cells.createRange, llamar al método JsonUtility.exportRangeToJson con referencias de Range y ExportRangeToJsonOptions y escribir datos JSON de cadena en el archivo a través de Método BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}