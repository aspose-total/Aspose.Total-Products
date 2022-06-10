---
title: Преобразование TSV в DOCX с помощью Java
description: Java API для экспорта TSV в DOCX с использованием Excel или Word
url_ignore: /ru/java/conversion/tsv-to-docx/
family: total
platformtag: net
feature: conversion
informat: TSV
outformat: DOCXX
otherformats: DOCX WORD PPTX POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API для экспорта TSV в DOCX" h2="Локальный Java API для экспорта TSV в DOCX, не полагаясь на Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование TSV в DOCX — это двухэтапный процесс. Сначала вы будете использовать API [Aspose.Cells для Java](https://products.aspose.com/cells/java) для преобразования данного документа TSV в PDF, а затем с помощью [Aspose.Pdf для Java](https://products.aspose.com/pdf/java) API, вы можете легко конвертировать PDF-документ в DOCX. Оба API входят в набор библиотек автоматизации форматов файлов [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать TSV в DOCX через Java API" %}}
1. Откройте файл TSV с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Преобразуйте TSV в PDF и установите для SaveFormat значение AUTO.
3. Загрузите преобразованный файл PDF с помощью класса [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
4. Сохраните документ в формате DOCX, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) метод и установите Docx как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы должны использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the TSV file using Workbook class
Workbook book = new Workbook("input.tsv");
// save TSV as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document Document = new Document("pdfOutput.pdf");
// save Document in DOCXX format
Document.save("output.docxx", com.aspose.pdf.SaveFormat.DocxX);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tsv-to-docxx/" name="TSV К DOCXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tsv-to-pptx/" name="TSV К PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tsv-to-powerpoint/" name="TSV К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/tsv-to-word/" name="TSV К WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}