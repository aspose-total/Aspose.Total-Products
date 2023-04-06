---
title: Konvertera XLTM till DOCX med .NET eller med gratis Online Converter
description: Konvertera XLTM till DOCX på .NET Framework, .NET Core, Mono eller Xamarin-plattformar eller online. Testa gratis CSV till DOC online-omvandlare snabbt innan du integrerar koden.

family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: DOCX
otherformats: DOC PPTX POWERPOINT WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="Konvertera XLTM till DOCX via C# eller onlineapp" h2="Exportera Excel&reg; XLTM till DOCX på .NET Framework, .NET Core, Mono eller Xamarin-plattformar">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="XLTM till DOCX-konvertering på .NET" %}}
1. Öppna XLTM-filen med klassen [Arbetsbok](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Konvertera XLTM till PDF och ställ in SaveFormat till Auto
3. Ladda den konverterade PDF-filen med klassen [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document)
4. Spara dokumentet i DOCX-format med metoden [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) och ställ in Docx som SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konverteringskrav" %}}
Installera från kommandoraden som ```nuget install Aspose.Total``` eller via Package Manager Console of Visual Studio med ```Install-Package Aspose.Total```.

Alternativt kan du hämta offline MSI-installationsprogrammet eller DLL-filer i en ZIP-fil från [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C#-kod för XLTM till DOCX-konvertering" gistPath="" %}}
```cs
// load the XLTM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltm");
// save XLTM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOCX format
document.Save("output.docx", SaveFormat.Docx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>Gratis onlinekonverterare för XLTM till DOCX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xltm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}