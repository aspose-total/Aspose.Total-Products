---
title: Convertir XLTM a POWERPOINT con C++
description: Convierta XLTM a POWERPOINT dentro de aplicaciones C++

family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: PPTX
otherformats: PPTX DOCX WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta XLTM a POWERPOINT a través de C++" h2="Exportar Excel<sup>&reg;</sup> XLTM a POWERPOINT dentro de aplicaciones C++ completamente funcionales" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversión de XLTM a POWERPOINT en C++" %}}
1. Abra el archivo XLTM usando [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) función miembro de [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) referencia de clase
2. Convierta XLTM a PDF y configure SaveFormat a Pdf
3. Cargue el archivo PDF convertido usando la referencia de clase [Powerpointumento](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument)
4. Guarde el powerpointumento en formato POWERPOINT usando la función miembro [Guardar](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) y configure Powerpoint como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLTM file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xltm");
// save XLTM as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xltm-to-pptx/" name="XLTM A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xltm-to-powerpointx/" name="XLTM A POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xltm-to-word/" name="XLTM A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xltm-to-powerpoint/" name="XLTM A POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}