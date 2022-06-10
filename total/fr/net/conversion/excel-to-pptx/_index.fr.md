---
title: Convertir EXCEL en PPTX avec .NET 
description: Convertir EXCEL en PPTX sur les plates-formes .NET Framework, .NET Core, Mono ou Xamarin
url: /fr/net/conversion/excel-to-pptx/
family: total
platformtag: net
feature: conversion
informat: CSV
outformat: PPTX
otherformats: DOC WORD POWERPOINT DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Convertir EXCEL en PPTX via C#" h2="Exporter Excel® EXCEL vers PPTX sur les plates-formes .NET Framework, .NET Core, Mono ou Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion EXCEL en PPTX sur .NET" %}}
1. Ouvrez le fichier EXCEL à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Convertissez EXCEL en PDF et définissez SaveFormat sur Auto
3. Chargez le fichier PDF converti à l'aide de la classe [Pptxument](https://apireference.aspose.com/pdf/net/aspose.pdf/pptxument)
4. Enregistrez le pptxument au format PPTX en utilisant la méthode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.pptxument/save/methods/5) et définissez Pptx comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Code .NET C# pour la conversion EXCEL en PPTX" gistPath="" %}}
```cs
// load the EXCEL file using Workbook class
var book = new Aspose.Cells.Workbook("input.excel");
// save EXCEL as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Pptxument class
var pptxument = new Aspose.Pdf.Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.Save("output.pptx", SaveFormat.Pptx); 
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