---
title: Convierta el formato JSON a MOBI a través de C++
description: C++ API t0 Parse JSON a MOBI sin usar Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: MOBI
otherformats: WORD FLATOPC DOT RTF DOCM WORDML CHM OTT PS DOTX EPUB ODT PCL DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta el formato JSON a MOBI a través de C++" h2="Analice JSON a MOBI dentro de aplicaciones C++ sin usar Microsoft<sup>&reg;</sup> Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al usar [Aspose.Total for C++](https://products.aspose.com/total/cpp/) puede analizar JSON a MOBI dentro de sus aplicaciones C++ en dos simples pasos. En primer lugar, al usar [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puede exportar JSON a PDF. Después de eso, usando [Aspose.Words for C++](https://products.aspose.com/words/cppp/), puede convertir PDF a MOBI. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato JSON a MOBI en C++" %}}
1. Cree un nuevo objeto [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) y lea los datos JSON válidos del archivo.
2. Guarde JSON como PDF utilizando el método [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Cargue el documento PDF usando la clase [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document)
4. Guarde el documento en formato MOBI usando el método [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Establecer diseño y convertir formato JSON a MOBI en C++" %}}
Mientras analiza JSON a MOBI, también puede establecer el tamaño de las filas y columnas cargando JSON con la clase [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Si necesita establecer el mismo alto de fila para todas las filas de la hoja de cálculo, puede hacerlo mediante [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) método de la colección [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). De manera similar, para establecer el mismo ancho de columna para todas las columnas de la hoja de cálculo, utilice el método [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) de la colección ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "set-layout-and-parse-json-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta el formato JSON a MOBI con marca de agua en C++" %}}
Usando la API, también puede analizar JSON a MOBI con marca de agua. Para agregar una marca de agua a su documento MOBI, primero puede convertir JSON a PDF y agregarle una marca de agua. Para agregar una marca de agua, cargue el archivo PDF recién creado usando la clase [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document), establezca diferentes propiedades para la marca de agua de texto,
llame al método SetText y pase el texto y el objeto de la marca de agua de TextWatermarkOptions. Después de agregar la marca de agua, puede guardar el documento en MOBI.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-word-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}