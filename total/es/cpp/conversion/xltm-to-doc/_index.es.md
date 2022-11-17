---
title: Convertir XLTM a DOC con C++
description: Convierta XLTM a DOC dentro de aplicaciones C++

family: total
platformtag: cpp
feature: conversion
informat: XLTM
outformat: DOC
otherformats: WORD POWERPOINT PPTX DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta XLTM a DOC a través de C++" h2="Exportar Excel<sup>&reg;</sup> XLTM a DOC dentro de aplicaciones C++ completamente funcionales" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversión de XLTM a DOC en C++" %}}
1. Abra el archivo XLTM usando [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) función miembro de [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) referencia de clase
2. Convierta XLTM a PDF y configure SaveFormat a Pdf
3. Cargue el archivo PDF convertido usando la referencia de clase [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Guarde el documento en formato DOC usando la función miembro [Guardar](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) y configure Doc como SaveFormat
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
// load the PDF file using Document class reference
auto doc = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOC format
doc->Save(u"convertedFile.doc", SaveFormat::Doc);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xltm-to-word/" name="XLTM A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xltm-to-powerpoint/" name="XLTM A POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xltm-to-pptx/" name="XLTM A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xltm-to-docx/" name="XLTM A DOCX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}