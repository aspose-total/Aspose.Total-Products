---
title: Convertir XLT en DOCX avec .NET 
description: Convertir XLT en DOCX sur les plates-formes .NET Framework, .NET Core, Mono ou Xamarin
url: /fr/net/conversion/xlt-to-docx/
family: total
platformtag: net
feature: conversion
informat: XLT
outformat: DOCX
otherformats: POWERPOINT WORD PPTX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir XLT en DOCX via C#" h2="Exporter Excel® XLT vers DOCX sur les plates-formes .NET Framework, .NET Core, Mono ou Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion XLT en DOCX sur .NET" %}}
1. Ouvrez le fichier XLT à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Convertissez XLT en PDF et définissez SaveFormat sur Auto
3. Chargez le fichier PDF converti à l'aide de la classe [Docxument](https://apireference.aspose.com/pdf/net/aspose.pdf/docxument)
4. Enregistrez le docxument au format DOCX en utilisant la méthode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.docxument/save/methods/5) et définissez Docx comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Code .NET C# pour la conversion XLT en DOCX" gistPath="" %}}
```cs
// load the XLT file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlt");
// save XLT as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Docxument class
var docxument = new Aspose.Pdf.Docxument("pdfOutput.pdf");
// save docxument in DOCXX format
docxument.Save("output.docxx", SaveFormat.DocxX); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Autres conversions prises en charge" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/csv-to-word/" name="CSV À WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/csv-to-powerpoint/" name="CSV À POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/csv-to-pptx/" name="CSV À PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/fr/net/conversion/csv-to-docx/" name="CSV À DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}