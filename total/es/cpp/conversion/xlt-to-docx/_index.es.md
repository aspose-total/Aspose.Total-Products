---
title: Convertir XLT a DOCX con C++
description: Convierta XLT a DOCX dentro de aplicaciones C++

family: total
platformtag: cpp
feature: conversion
informat: XLT
outformat: DOCX
otherformats: DOC PPTX WORD POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Convierta XLT a DOCX a través de C++" h2="Exportar Excel<sup>&reg;</sup> XLT a DOCX dentro de aplicaciones C++ completamente funcionales" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Conversión de XLT a DOCX en C++" %}}
1. Abra el archivo XLT usando [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) función miembro de [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) referencia de clase
2. Convierta XLT a PDF y configure SaveFormat a Pdf
3. Cargue el archivo PDF convertido usando la referencia de clase [Documento](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document)
4. Guarde el documento en formato DOCX usando la función miembro [Guardar](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#a6383c010776212483f51cc41235924db) y configure Docx como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversión" %}}
Instale desde la línea de comandos como ```nuget install Aspose.Total.Cpp``` o a través de Package Manager Console de Visual Studio con ```Install-Package Aspose.Total.Cpp```.

Como alternativa, obtenga el instalador MSI sin conexión o las DLL en un archivo ZIP desde [descargas](https://downloads.aspose.com/total/cpp).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLT file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlt");
// save XLT as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Document class reference
auto docx = MakeObject<Document>(u"pdfOutput.pdf");
// save document in DOCX format
docx->Save(u"convertedFile.docx", SaveFormat::DocxX);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Otras conversiones admitidas" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xlt-to-docx/" name="XLT A DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xlt-to-pptx/" name="XLT A PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xlt-to-word/" name="XLT A WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/es/cpp/conversion/xlt-to-powerpoint/" name="XLT A POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}