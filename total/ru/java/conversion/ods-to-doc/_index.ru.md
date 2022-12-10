---
title: Преобразование ODS в DOC с помощью Java
description: Java API для экспорта ODS в DOC с использованием Excel или Word
url_ignore: /ru/java/conversion/ods-to-doc/
family: total
platformtag: net
feature: conversion
informat: ODS
outformat: DOC
otherformats: DOCX POWERPOINT WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API для экспорта ODS в DOC" h2="Локальный Java API для экспорта ODS в DOC, не полагаясь на Microsoft Excel&reg;" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование ODS в DOC — это двухэтапный процесс. Сначала вы будете использовать API [Aspose.Cells для Java](https://products.aspose.com/cells/java) для преобразования данного документа ODS в PDF, а затем с помощью [Aspose.Pdf для Java](https://products.aspose.com/pdf/java) API, вы можете легко конвертировать PDF-документ в DOC. Оба API входят в набор библиотек автоматизации форматов файлов [Aspose.Total for Java](https://products.aspose.com/total/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать ODS в DOC через Java API" %}}
1. Откройте файл ODS с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Преобразуйте ODS в PDF и установите для SaveFormat значение AUTO.
3. Загрузите преобразованный файл PDF с помощью класса [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document).
4. Сохраните документ в формате DOC, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions-) метод и установите Doc как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы должны использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the ODS file using Workbook class
Workbook book = new Workbook("input.ods");
// save ODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Document class
Document document = new Document("pdfOutput.pdf");
// save document in DOC format
document.save("output.doc", com.aspose.pdf.SaveFormat.Doc);  
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ods-to-docx/" name="ODS К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ods-to-pptx/" name="ODS К PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ods-to-powerpoint/" name="ODS К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ods-to-word/" name="ODS К WORD" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}