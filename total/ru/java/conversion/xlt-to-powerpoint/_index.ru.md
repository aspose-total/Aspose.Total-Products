---
title: Преобразование XLT в POWERPOINT с помощью Java
description: Java API для экспорта XLT в POWERPOINT с использованием Excel или Word
url_ignore: /ru/java/conversion/xlt-to-powerpoint/
family: total
platformtag: net
feature: conversion
informat: XLT
outformat: PPTX
otherformats: POWERPOINTX PPTX WORD POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API для экспорта XLT в POWERPOINT" h2="Локальный Java API для экспорта XLT в POWERPOINT, не полагаясь на Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование XLT в POWERPOINT — это двухэтапный процесс. Сначала вы будете использовать API [Aspose.Cells для Java](https://products.aspose.com/cells/java) для преобразования данного документа XLT в PDF, а затем с помощью [Aspose.Pdf для Java](https://products.aspose.com/pdf/java) API, вы можете легко конвертировать PDF-документ в POWERPOINT. Оба API входят в набор библиотек автоматизации форматов файлов [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать XLT в POWERPOINT через Java API" %}}
1. Откройте файл XLT с помощью класса [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Преобразуйте XLT в PDF и установите для SaveFormat значение AUTO.
3. Загрузите преобразованный файл PDF с помощью класса [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
4. Сохраните документ в формате POWERPOINT, используя [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) метод и установите Powerpoint как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы должны использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLT file using Workbook class
Workbook book = new Workbook("input.xlt");
// save XLT as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in PPTX format
document.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlt-to-powerpointx/" name="XLT К POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlt-to-pptx/" name="XLT К PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlt-to-powerpoint/" name="XLT К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xlt-to-word/" name="XLT К WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}