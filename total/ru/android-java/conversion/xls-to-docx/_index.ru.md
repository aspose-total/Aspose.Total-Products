---
title: Экспорт XLS в DOCX на Android
description: Android API для преобразования XLS в DOCX без использования Microsoft Word
url: /ru/android-java/conversion/xls-to-docx/
family: total
platformtag: cpp
feature: conversion
informat: XLS
outformat: DOCX
otherformats: WORD DOC POWERPOINT PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг XLS в DOCX на Android через Java" h2="Преобразование XLS в DOCX в приложениях для Android без использования Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total для Android через Java](https://products.aspose.com/total/android-java/) — это пакет мощных API автоматизации файлов. Используя два его API, вы можете интегрировать функцию преобразования XLS в DOCX в свои приложения для Android. На первом этапе вы можете экспортировать XLS в PDF с помощью [Aspose.Cells для Android через Java](https://products.aspose.com/cells/android-java/). После этого, используя [Aspose.PDF для Android через Java](https://products.aspose.com/pdf/android-java/), вы можете конвертировать PDF в DOCX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для экспорта XLS в DOCX" %}}
1. Откройте файл XLS с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Преобразуйте XLS в PDF и установите для параметра SaveFormat значение AUTO.
3. Загрузите преобразованный файл PDF с помощью класса [Docxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument).
4. Сохраните документ в формате DOCX, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Docxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) метод
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.PDF для Android через Java](https://docxs.aspose.com/pdf/androidjava/installation/) и [Aspose.Cells для Android через Java](https://docxs.aspose.com/cells /java/aspose-cells-for-android-через-java-установку/#install-asposecells-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// save XLS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Docxument class
Docxument docxument = new Docxument("pdfOutput.pdf");
// save docxument in DOCX format
docxument.save("output.docx", com.aspose.pdf.SaveFormat.DocxX);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Удалить пользовательские свойства из файла XLS в Android через Java" %}}
Помимо преобразования документов, [Aspose.Cells для Android через Java](https://products.aspose.com/cells/android-java/) также предоставляет множество других функций. Перед процессом преобразования вы можете удалить пользовательские свойства XLS-документа. Чтобы удалить настраиваемые свойства, вызовите метод [DocxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/docxumentpropertycollection#remove(java.lang.String)) и передайте имя свойство документа, которое необходимо удалить.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the XLS file using Workbook class
Workbook book = new Workbook("input.xls");
// retrieve a list of all custom docxument properties of the Excel file
DocxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomDocxumentProperties();
// remove a custom docxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xls-to-word/" name="XLS К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xls-to-docx/" name="XLS К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xls-to-powerpoint/" name="XLS К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/xls-to-pptx/" name="XLS К PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}