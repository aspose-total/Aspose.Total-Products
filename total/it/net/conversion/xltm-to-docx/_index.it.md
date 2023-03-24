---
title: Converti XLTM in DOCX con .NET o con il convertitore online gratuito
description: Converti XLTM in DOCX su piattaforme .NET Framework, .NET Core, Mono o Xamarin o in linea. Prova rapidamente il convertitore online gratuito da CSV a DOC prima di integrare il codice.

family: total
platformtag: net
feature: conversion
informat: XLTM
outformat: DOCX
otherformats: DOC PPTX POWERPOINT WORD
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Converti XLTM in DOCX tramite C# o App online" h2="Esporta Excel&reg; XLTM a DOCX su piattaforme .NET Framework, .NET Core, Mono o Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Conversione da XLTM a DOCX su .NET" %}}
1. Aprire il file XLTM utilizzando la classe [Workbook](https://apiference.aspose.com/cells/net/aspose.cells/workbook)
2. Converti XLTM in PDF e imposta SaveFormat su Auto
3. Caricare il file PDF convertito utilizzando la classe [Document](https://apiference.aspose.com/pdf/net/aspose.pdf/document)
4. Salva il documento in formato DOCX utilizzando il metodo [Salva](https://apiference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) e imposta Docx come SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisiti di conversione" %}}
Installa dalla riga di comando come ```nuget install Aspose.Total``` o tramite Package Manager Console di Visual Studio con ```Install-Package Aspose.Total```.

In alternativa, scarica il programma di installazione MSI offline o le DLL in un file ZIP da [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Codice .NET C# per la conversione da XLTM a DOCX" gistPath="" %}}
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

<h3>Convertitore online gratuito da XLTM a DOCX</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=xltm" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}