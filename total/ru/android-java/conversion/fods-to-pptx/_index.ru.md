---
title: Экспорт FODS в PPTX на Android
description: Android API для преобразования FODS в PPTX без использования Microsoft Word
url: /ru/android-java/conversion/fods-to-pptx/
family: total
platformtag: cpp
feature: conversion
informat: FODS
outformat: PPTX
otherformats: WORD POWERPOINT DOCX DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг FODS в PPTX на Android через Java" h2="Преобразование FODS в PPTX в приложениях для Android без использования Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total для Android через Java](https://products.aspose.com/total/android-java/) — это пакет мощных API автоматизации файлов. Используя два его API, вы можете интегрировать функцию преобразования FODS в PPTX в свои приложения для Android. На первом этапе вы можете экспортировать FODS в PDF с помощью [Aspose.Cells для Android через Java](https://products.aspose.com/cells/android-java/). После этого, используя [Aspose.PDF для Android через Java](https://products.aspose.com/pdf/android-java/), вы можете конвертировать PDF в PPTX. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для экспорта FODS в PPTX" %}}
1. Откройте файл FODS с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Преобразуйте FODS в PDF и установите для параметра SaveFormat значение AUTO.
3. Загрузите преобразованный файл PDF с помощью класса [Pptxument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument).
4. Сохраните документ в формате PPTX, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Pptxument#save-java.lang.String-com.aspose.pdf.SaveOptions -) метод
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.PDF для Android через Java](https://pptxs.aspose.com/pdf/androidjava/installation/) и [Aspose.Cells для Android через Java](https://pptxs.aspose.com/cells /java/aspose-cells-for-android-через-java-установку/#install-asposecells-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// save FODS as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Pptxument class
Pptxument pptxument = new Pptxument("pdfOutput.pdf");
// save pptxument in PPTX format
pptxument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Удалить пользовательские свойства из файла FODS в Android через Java" %}}
Помимо преобразования документов, [Aspose.Cells для Android через Java](https://products.aspose.com/cells/android-java/) также предоставляет множество других функций. Перед процессом преобразования вы можете удалить пользовательские свойства FODS-документа. Чтобы удалить настраиваемые свойства, вызовите метод [PptxumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/pptxumentpropertycollection#remove(java.lang.String)) и передайте имя свойство документа, которое необходимо удалить.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the FODS file using Workbook class
Workbook book = new Workbook("input.fods");
// retrieve a list of all custom pptxument properties of the Excel file
PptxumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPptxumentProperties();
// remove a custom pptxument property
customProperties.remove("Publisher"); 
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/fods-to-word/" name="FODS К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/fods-to-powerpoint/" name="FODS К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/fods-to-pptxx/" name="FODS К PPTXX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/fods-to-pptx/" name="FODS К PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}