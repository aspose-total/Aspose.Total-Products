---
title: API de C++ para convertir MHTML a MD
description: Convierta MHTML a MD a través de la API de C++ sin usar Microsoft Excel o Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: MHTML
outformat: MD
otherformats: CSV FODS ODS TXT XLTM EXCEL DIF XLSM XLT XLAM TSV SXC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar MHTML a MD en aplicaciones C++" h2="Convierta MHTML a MD en aplicaciones C++ nativas sin necesidad de Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Convertir MHTML a MD en C++ a través de las bibliotecas de automatización de formato de archivo [Aspose.Total for C++](https://products.aspose.com/total/cpp/) es un proceso simple de dos pasos. En el primer paso, puede exportar MHTML a XLSX usando [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), luego, usando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API de programación de hojas de cálculo, puede convertir XLSX a MD. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir MHTML a MD" %}}
1. Abra el archivo MHTML usando la referencia de clase [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Convierta MHTML a XLSX usando la función miembro [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Cargue el documento XLSX utilizando la referencia de clase [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Guarde el documento en formato MD usando la función miembro [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga o establezca la información del archivo MHTML a través de C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) también le permite obtener información sobre su documento MHTML y le permite tomar decisiones informadas antes de su proceso de conversión. Para obtener información específica de un archivo MHTML, primero debe llamar al método [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) de [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) clase. Una vez que se recupera el objeto DocumentInfo, puede obtener los valores de las propiedades individuales. Además, también puede establecer las propiedades utilizando los métodos respectivos de la clase DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Guarde el formato de archivo MD para transmitir a través de C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) permite guardar el formato de archivo MD para transmitir. Para guardar archivos en una secuencia, cree un objeto MemoryStream o FileStream y guarde el archivo en ese objeto de secuencia llamando al [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) del objeto. Especifique el formato de archivo deseado mediante la enumeración [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) al llamar al método Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-md-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}