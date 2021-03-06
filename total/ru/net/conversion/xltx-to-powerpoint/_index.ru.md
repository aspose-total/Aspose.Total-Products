---
title: Конвертируйте XLTX в POWERPOINT с помощью .NET 
description: Преобразование XLTX в POWERPOINT на платформах .NET Framework, .NET Core, Mono или Xamarin
url_ignore: /ru/net/conversion/xltx-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLTX
outformat: PPTX
otherformats: DOCX DOC WORD PPTX
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="Преобразование XLTX в POWERPOINT через C#" h2="Экспорт Excel&reg; XLTX в POWERPOINT на платформах .NET Framework, .NET Core, Mono или Xamarin.">}}
{{< blocks/products/pf/main-container >}}



{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Преобразование XLTX в POWERPOINT на .NET" %}}
1. Откройте файл XLTX с помощью класса [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook).
2. Преобразуйте XLTX в PDF и установите для параметра SaveFormat значение Auto.
3. Загрузите преобразованный файл PDF с помощью класса [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document).
4. Сохраните документ в формате PPTX с помощью метода [Сохранить](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) и установите Pptx как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).(https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="Код .NET C# для преобразования XLTX в POWERPOINT" gistPath="" %}}

```cs// load the XLTX file using Workbook class
var book = new Aspose.Cells.Workbook("input.xltx");
// save XLTX as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in PPTX format
document.Save("output.pptx", SaveFormat.Pptx); 
```

{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xltx-to-docx/" name="XLTX в DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xltx-to-doc/" name="XLTX в DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xltx-to-word/" name="XLTX в WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xltx-to-pptx/" name="XLTX в PPTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}