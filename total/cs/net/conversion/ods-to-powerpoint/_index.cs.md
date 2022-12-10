---
title: Převeďte ODS na POWERPOINT pomocí .NET 
description: Převeďte ODS na POWERPOINT na platformách .NET Framework, .NET Core, Mono nebo Xamarin

family: total
platformtag: net
feature: conversion
informat: ODS
outformat: PPTX
otherformats: DOC PPTX WORD DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Převést ODS na POWERPOINT přes C#" h2="Export Excel&reg; ODS do POWERPOINT na platformách .NET Framework, .NET Core, Mono nebo Xamarin">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Převod ODS na POWERPOINT na .NET" %}}
1. Otevřete soubor ODS pomocí třídy [Sešit](https://apireference.aspose.com/cells/net/aspose.cells/workbook)
2. Převeďte ODS na PDF a nastavte SaveFormat na Auto
3. Načtěte převedený soubor PDF pomocí třídy [Powerpointument](https://apireference.aspose.com/pdf/net/aspose.pdf/powerpointument)
4. Uložte dokument do formátu POWERPOINT pomocí metody [Uložit](https://apireference.aspose.com/pdf/net/aspose.pdf.powerpointument/save/methods/5) a nastavte Powerpoint jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Instalujte z příkazového řádku jako ```nuget install Aspose.Total``` nebo prostřednictvím konzoly Správce balíčků sady Visual Studio s ```Install-Package Aspose.Total```.

Případně si stáhněte offline instalační program MSI nebo knihovny DLL v souboru ZIP z [stažení](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title=".NET C# Kód pro převod ODS na POWERPOINT" gistPath="" %}}
```cs
// load the ODS file using Workbook class
var book = new Aspose.Cells.Workbook("input.ods");
// save ODS as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Powerpointument class
var powerpointument = new Aspose.Pdf.Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.Save("output.pptx", SaveFormat.Pptx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/other-supported-section title="Další podporované konverze" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/csv-to-word/" name="CSV Na WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/csv-to-powerpoint/" name="CSV Na POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/csv-to-pptx/" name="CSV Na PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/csv-to-docx/" name="CSV Na DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}