---
title: Преобразование XLSM в DOC с помощью .NET 
description: Преобразование XLSM в DOC на платформах .NET Framework, .NET Core, Mono или Xamarin.
url: /ru/net/conversion/xlsm-to-doc/
family: total
platformtag: net
feature: conversion
informat: XLSM
outformat: DOC
otherformats: DOCX WORD POWERPOINT PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразование XLSM в DOC через C#" h2="Экспорт Excel&reg; XLSM в DOC на платформах .NET Framework, .NET Core, Mono или Xamarin.">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Преобразование XLSM в DOC на .NET" %}}
1. Откройте файл XLSM, используя класс [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook).
2. Преобразуйте XLSM в PDF и установите для параметра SaveFormat значение Auto.
3. Загрузите преобразованный файл PDF с помощью класса [Документ](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
4. Сохраните документ в формате DOC с помощью метода [Сохранить](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) и установите документ как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).(https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код .NET C# для преобразования XLSM в DOC" gistPath="" %}}

```cs// load the XLSM file using Workbook class
var book = new Aspose.Cells.Workbook("input.xlsm");
// save XLSM as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in DOC format
document.Save("output.doc", SaveFormat.Doc); 
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlsm-to-docx/" name="XLSM в DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlsm-to-word/" name="XLSM в WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlsm-to-powerpoint/" name="XLSM в POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlsm-to-pptx/" name="XLSM в PPTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}