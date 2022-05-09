---
title: Преобразование FODS в WORD с помощью Java
description: Java API для экспорта FODS в WORD с использованием Excel или Word
url_ignore: /ru/java/conversion/fods-to-word/
family: total
platformtag: net
feature: conversion
informat: FODS
outformat: WORD
otherformats: PPTX WORD WORDX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API для экспорта FODS в WORD" h2="Локальный Java API для экспорта FODS в WORD, не полагаясь на Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование FODS в WORD — это двухэтапный процесс. Сначала вы будете использовать API [Aspose.Cells для Java](https://products.aspose.com/cells/java) для преобразования данного документа FODS в PDF, а затем с помощью [Aspose.Pdf для Java](https://products.aspose.com/pdf/java) API, вы можете легко конвертировать PDF-документ в WORD. Оба API входят в набор библиотек автоматизации форматов файлов [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать FODS в WORD через Java API" %}}
1. Откройте файл FODS с помощью класса [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Преобразуйте FODS в PDF и установите для SaveFormat значение AUTO.
3. Загрузите преобразованный файл PDF с помощью класса [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document).
4. Сохраните документ в формате WORD, используя [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) метод и установите Word как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы должны использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in WORD format
document.save("output.word", com.aspose.pdf.SaveFormat.Word);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/fods-to-wordx/" name="FODS К WORDX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/fods-to-pptx/" name="FODS К PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/fods-to-powerpoint/" name="FODS К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/fods-to-word/" name="FODS К WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}