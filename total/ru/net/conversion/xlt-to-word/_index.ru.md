---
title: Преобразование XLT в WORD с помощью .NET 
description: Преобразование XLT в WORD на платформах .NET Framework, .NET Core, Mono или Xamarin
url: /ru/net/conversion/xlt-to-word/
family: total
platformtag: net
feature: conversion
informat: XLT
outformat: DOC
otherformats: DOC DOCX POWERPOINT PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Конвертировать XLT в WORD через C#" h2="Экспорт Excel&reg; XLT в WORD на платформах .NET Framework, .NET Core, Mono или Xamarin">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Преобразование XLT в WORD на .NET" %}}
1. Откройте файл XLT с помощью класса [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
2. Преобразуйте XLT в PDF и установите для параметра SaveFormat значение Auto.
3. Загрузите преобразованный файл PDF с помощью класса [Документ](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
4. Сохраните документ в формате DOC с помощью метода [Сохранить](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) и установите документ как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).(https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код .NET C# для преобразования XLT в WORD" gistPath="" %}}

```cs// load the XLT file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlt");
// save XLT as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlt-to-doc/" name="XLT в DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlt-to-docx/" name="XLT в DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlt-to-powerpoint/" name="XLT в POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlt-to-pptx/" name="XLT в PPTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}