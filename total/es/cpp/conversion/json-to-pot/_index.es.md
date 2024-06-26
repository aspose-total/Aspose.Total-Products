---
title: Convierta el formato JSON a POT a través de C++
description: Analizar JSON a POT en C++ sin usar Microsoft PowerPoint

family: total
platformtag: cpp
feature: conversion
informat: JSON
outformat: POT
otherformats: OTP ODP PPSX PPT POTM PPS PPTM POTX PPSM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta el formato JSON a POT a través de C++" h2="API C++ para analizar JSON a POT sin usar Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Puede convertir JSON a POT dentro de cualquier aplicación C++ en dos simples pasos. En primer lugar, al usar [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puede analizar JSON a PPTX. Después de eso, usando [Aspose.Slides for C++](https://products.aspose.com/slides/cpp/), puede convertir PPTX a POT. Ambas API se incluyen en el paquete [Aspose.Total for C++](https://products.aspose.com/total/cpp/). 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta el formato JSON a POT a través de C++" %}}
1. Cree un nuevo objeto [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) y lea los datos JSON válidos del archivo.
2. Guarde JSON como PPTX usando el método [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
3. Cargue el documento PPTX usando la clase [Presentación](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation)
4. Guarde el documento en formato POT usando el método [Save](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation#afcd59ec697bf05c10f78c3869de2ec9e)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "convert-json-to-powerpoint.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Establezca el diseño y convierta el formato JSON a POT a través de C++" %}}
Mientras analiza JSON a POT, también puede establecer el tamaño de filas y columnas cargando JSON con la clase [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook). Si necesita establecer el mismo alto de fila para todas las filas de la hoja de cálculo, puede hacerlo mediante [SetStandardHeight](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a0b79a3163e2b601aa1b6a6a1e3f1467f ) método de la colección [ICells](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell). De manera similar, para establecer el mismo ancho de columna para todas las columnas de la hoja de cálculo, utilice el método [SetStandardWidth](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_cell#a48f5dbccc3bf4bb9e6e882094b500bd7) de la colección ICells.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "set-layout-and-parse-json-to-powerpoint.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Convierta el formato JSON a POT con marca de agua en C++" %}}
Usando la API, también puede convertir JSON a POT con marca de agua. Para agregar una marca de agua a su documento POT, primero puede analizar JSON a PPTX y agregarle una marca de agua. Para agregar una marca de agua, cargue el archivo PPTX recién creado usando la clase [Presentación](https://reference.aspose.com/slides/cpp/class/aspose.slides.presentation), obtenga la primera diapositiva, agregue una AutoForma de tipo Rectángulo, agregue Marco de texto al Rectángulo, cree el objeto Párrafo para un marco de texto, cree un objeto Porción para el párrafo, agregue una marca de agua usando set_Text() y puede guardar el documento en POT.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e6b7f7744296b6d7ad8619a0769d75be" "parse-json-to-powerpoint-with-watermark.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}