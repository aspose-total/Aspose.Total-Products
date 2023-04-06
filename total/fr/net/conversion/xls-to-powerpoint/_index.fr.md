---
title: Convertir XLS en POWERPOINT avec .NET ou avec le convertisseur en ligne gratuit
description: Convertir XLS en POWERPOINT sur les plates-formes .NET Framework, .NET Core, Mono ou Xamarin ou en ligne. Testez rapidement le convertisseur en ligne CSV vers DOC gratuit avant d'intégrer le code.

family: total
platformtag: net
feature: conversion
informat: XLS
outformat: PPTX
otherformats: PPTX WORD DOCX DOC
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Convertir XLS en POWERPOINT via C# ou application en ligne" h2="Exporter Excel® XLS vers POWERPOINT sur les plates-formes .NET Framework, .NET Core, Mono ou Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversion XLS en POWERPOINT sur .NET" %}}
1. Ouvrez le fichier XLS à l'aide de la classe [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Convertissez XLS en PDF et définissez SaveFormat sur Auto
3. Chargez le fichier PDF converti à l'aide de la classe [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. Enregistrez le powerpointument au format POWERPOINT en utilisant la méthode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) et définissez Powerpoint comme SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Exigences de conversion" %}}
Installez à partir de la ligne de commande en tant que ```nuget install Aspose.Total``` ou via la console du gestionnaire de packages de Visual Studio avec ```Install-Package Aspose.Total```.

Vous pouvez également obtenir le programme d'installation MSI hors ligne ou les DLL dans un fichier ZIP à partir de [téléchargements](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Code .NET C# pour la conversion XLS en POWERPOINT" gistPath="" %}}
```cs
// load the XLS file using Workbook class
var book = new Aspose.Cells.Workbook("input.xls");
// save XLS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Convertisseur en ligne gratuit pour XLS en POWERPOINT</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xls" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}