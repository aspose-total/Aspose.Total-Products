---
title: Convertir EXCEL en POWERPOINT avec .NET 
description: Convertir EXCEL en POWERPOINT sur les plates-formes .NET Framework, .NET Core, Mono ou Xamarin

family: total
platformtag: net
feature: conversion
informat: EXCEL
outformat: POWERPOINT
otherformats: WORD PPTX DOCX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Convertir EXCEL en POWERPOINT via C#" h2="Exporter Excel® EXCEL vers POWERPOINT sur les plates-formes .NET Framework, .NET Core, Mono ou Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion EXCEL en POWERPOINT sur .NET" %}}
1. Ouvrez le fichier EXCEL à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Convertissez EXCEL en PDF et définissez SaveFormat sur Auto
3. Chargez le fichier PDF converti à l'aide de la classe [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. Enregistrez le powerpointument au format POWERPOINT en utilisant la méthode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) et définissez Powerpoint comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Code .NET C# pour la conversion EXCEL en POWERPOINT" gistPath="" %}}
```cs
// load the EXCEL file using Workbook class
var book = new Aspose.Cells.Workbook("input.excel");
// save EXCEL as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}