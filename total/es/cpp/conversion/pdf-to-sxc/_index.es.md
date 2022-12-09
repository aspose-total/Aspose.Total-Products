---
title: API de C++ para convertir PDF a SXC
description: Convierta PDF a SXC a través de la API de C++ sin usar Microsoft Excel o Adobe Reader

family: total
platformtag: cpp
feature: conversion
informat: PDF
outformat: SXC
otherformats: TXT TSV ODS XLTX XLT DIF EXCEL XLSB XLTM FODS MD XLSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Renderizar PDF a SXC en aplicaciones C++" h2="Convierta PDF a SXC en aplicaciones C++ nativas sin necesidad de Microsoft<sup>&reg;</sup> Excel o Adobe<sup>&reg;</sup> Acrobat Reader" >}}

{{% blocks/products/pf/feature-page-summary %}}
Convertir PDF a SXC en C++ a través de las bibliotecas de automatización de formato de archivo [Aspose.Total for C++](https://products.aspose.com/total/cpp/) es un proceso simple de dos pasos. En el primer paso, puede exportar PDF a XLSX usando [Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/), luego, usando [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/) API de programación de hojas de cálculo, puede convertir XLSX a SXC. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API de C++ para convertir PDF a SXC" %}}
1. Abra el archivo PDF usando la referencia de clase [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
2. Convierta PDF a XLSX usando la función miembro [Guardar](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db)
3. Cargue el documento XLSX utilizando la referencia de clase [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook)
4. Guarde el documento en formato SXC usando la función miembro [Guardar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997)
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://releases.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "convert-pdf-to-excel.cpp" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenga o establezca la información del archivo PDF a través de C++" %}}
[Aspose.PDF for C++](https://products.aspose.com/pdf/cpp/) también le permite obtener información sobre su documento PDF y le permite tomar decisiones informadas antes de su proceso de conversión. Para obtener información específica de un archivo PDF, primero debe llamar al método [get_Info()](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#ae7a6ba620499ffa0dbaa5c813ee96c4a) de [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) clase. Una vez que se recupera el objeto DocumentInfo, puede obtener los valores de las propiedades individuales. Además, también puede establecer las propiedades utilizando los métodos respectivos de la clase DocumentInfo.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "get-pdf-information.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Guarde el formato de archivo SXC para transmitir a través de C++" %}}
[Aspose.Cells for C++](https://products.aspose.com/cells/net/) permite guardar el formato de archivo SXC para transmitir. Para guardar archivos en una secuencia, cree un objeto MemoryStream o FileStream y guarde el archivo en ese objeto de secuencia llamando al [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) [Guardar](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a77072cfb929787df9ad1f38b02f58349) del objeto. Especifique el formato de archivo deseado mediante la enumeración [SaveFormat](https://reference.aspose.com/cells/cpp/namespace/aspose.cells#a11cae527e4e68f1adcac8f47ea64481a) al llamar al método Save.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "9acc2aa5d80558015276a9ba295cd309" "save-sxc-to-stream.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-txt/" name="PDF A TXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-tsv/" name="PDF A TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-ods/" name="PDF A ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-xltx/" name="PDF A XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-xlt/" name="PDF A XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-dif/" name="PDF A DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-excel/" name="PDF A EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-xlsb/" name="PDF A XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-xltm/" name="PDF A XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-fods/" name="PDF A FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-md/" name="PDF A MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/pdf-to-xlsm/" name="PDF A XLSM" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}