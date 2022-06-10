---
title: Преобразование EXCEL в PPTX с помощью .NET 
description: Преобразование EXCEL в PPTX на платформах .NET Framework, .NET Core, Mono или Xamarin
url_ignore: /ru/net/conversion/excel-to-pptx/
family: total
platformtag: net
feature: conversion
informat: CSV
outformat: PPTX
otherformats: DOC WORD POWERPOINT DOCX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразование EXCEL в PPTX через C#" h2="Экспорт Excel&reg; EXCEL в PPTX на платформах .NET Framework, .NET Core, Mono или Xamarin">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Преобразование EXCEL в PPTX на .NET" %}}
1. Откройте файл EXCEL с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
2. Преобразуйте EXCEL в PDF и установите для параметра SaveFormat значение Auto.
3. Загрузите преобразованный файл PDF с помощью класса [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document).
4. Сохраните документ в формате PPTX с помощью метода [Сохранить](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) и установите Pptx как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).(https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код .NET C# для преобразования EXCEL в PPTX" gistPath="" %}}

```cs// load the EXCEL file using Workbook class
var book = new Aspose.Cells.Workbook("input.csv");
// save EXCEL as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in PPTX format
document.Save("output.pptx", SaveFormat.Pptx); 
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/csv-to-doc/" name="CSV в DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/csv-to-word/" name="CSV в WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/csv-to-powerpoint/" name="CSV в POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/csv-to-docx/" name="CSV в DOCX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}