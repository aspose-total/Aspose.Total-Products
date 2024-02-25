---
title: Convierta el formato DOTX a JSON en C++
description: Exporte DOTX a JSON en C++ sin usar Microsoft Excel o Word

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta DOTX a formato JSON a través de C++" h2="Exporte DOTX a JSON a través de C++ sin usar Microsoft<sup>&reg;</sup> Word o Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Al usar [Aspose.Total for C++](https://products.aspose.com/total/cpp/) puede convertir el formato DOTX a JSON dentro de sus aplicaciones C++. En primer lugar, al usar [Aspose.Words for C++](https://products.aspose.com/words/cpp/), puede exportar DOTX a HTML. Después de eso, usando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/), puede convertir HTML a formato JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Convierta DOTX a formato JSON a través de C++" %}}
1. Abra el archivo DOTX usando la referencia de clase [Dotxumento](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument)
2. Convierta DOTX a HTML usando la función miembro [Save](https://reference.aspose.com/words/cpp/class/aspose.words.dotxument#save_string_saveformat)
3. Cargue el dotxumento HTML utilizando la referencia de clase [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Guarde el dotxumento en formato JSON usando la función miembro [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-word-to-json.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Convierta DOTX protegido a formato JSON a través de C++" %}}
Usando la API, también puede abrir el dotxumento protegido por contraseña. Si su dotxumento DOTX de entrada está protegido con contraseña, no puede convertirlo al formato JSON sin usar la contraseña. Para hacer esto, use una sobrecarga de constructor especial, que acepta un objeto LoadOptions. Este objeto contiene la propiedad Password, que especifica la cadena de contraseña.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4f603d2b56d75433007748b6ccb6640b" "convert-protected-word-to-json.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}