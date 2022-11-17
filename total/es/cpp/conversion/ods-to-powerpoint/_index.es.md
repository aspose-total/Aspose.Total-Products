---
title: Convertir ODS a POWERPOINT con C++
description: Convierta ODS a POWERPOINT dentro de aplicaciones C++

family: total
platformtag: cpp
feature: conversion
informat: ODS
outformat: PPTX
otherformats: DOCX PPTX WORD DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta ODS a POWERPOINT a través de C++" h2="Exportar Excel<sup>&reg;</sup> ODS a POWERPOINT dentro de aplicaciones C++ completamente funcionales" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversión de ODS a POWERPOINT en C++" %}}
1. Abra el archivo ODS usando [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) función miembro de [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) referencia de clase
2. Convierta ODS a PDF y configure SaveFormat a Pdf
3. Cargue el archivo PDF convertido usando la referencia de clase [Powerpointumento](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument)
4. Guarde el powerpointumento en formato POWERPOINT usando la función miembro [Guardar](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) y configure Powerpoint como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.ods");
// save ODS as PDF
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
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ods-to-powerpointx/" name="ODS A POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ods-to-pptx/" name="ODS A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ods-to-word/" name="ODS A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/ods-to-powerpoint/" name="ODS A POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}