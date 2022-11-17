---
title: Экспорт SXC в POWERPOINT на Android
description: Android API для преобразования SXC в POWERPOINT без использования Microsoft Word

family: total
platformtag: cpp
feature: conversion
informat: SXC
outformat: PPTX
otherformats: DOCX DOC WORD PPTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Рендеринг SXC в POWERPOINT на Android через Java" h2="Преобразование SXC в POWERPOINT в приложениях для Android без использования Microsoft<sup>&reg;</sup> Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/) — это пакет мощных API автоматизации файлов. Используя два его API, вы можете интегрировать функцию преобразования SXC в POWERPOINT в свои приложения для Android. На первом этапе вы можете экспортировать SXC в PDF с помощью [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/). После этого, используя [Aspose.PDF for Android via Java](https://products.aspose.com/pdf/android-java/), вы можете конвертировать PDF в POWERPOINT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Android API для экспорта SXC в POWERPOINT" %}}
1. Откройте файл SXC с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
2. Преобразуйте SXC в PDF и установите для параметра SaveFormat значение AUTO.
3. Загрузите преобразованный файл PDF с помощью класса [Powerpointument](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument).
4. Сохраните документ в формате POWERPOINT, используя [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Powerpointument#save-java.lang.String-com.aspose.pdf.SaveOptions -) метод
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.PDF for Android via Java](https://powerpoints.aspose.com/pdf/androidjava/installation/) и [Aspose.Cells for Android via Java](https://powerpoints.aspose.com/cells /java/aspose-cells-for-android-через-java-установку/#install-asposecells-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// save SXC as PDF
book.save("pdfOutput.pdf", com.aspose.cells.SaveFormat.AUTO);
// load the PDF file using Powerpointument class
Powerpointument powerpointument = new Powerpointument("pdfOutput.pdf");
// save powerpointument in PPTX format
powerpointument.save("output.pptx", com.aspose.pdf.SaveFormat.Pptx);    
```


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Удалить пользовательские свойства из файла SXC в Android через Java" %}}
Помимо преобразования документов, [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/) также предоставляет множество других функций. Перед процессом преобразования вы можете удалить пользовательские свойства SXC-документа. Чтобы удалить настраиваемые свойства, вызовите метод [PowerpointumentPropertyCollection.remove](https://reference.aspose.com/cells/java/com.aspose.cells/powerpointumentpropertycollection#remove(java.lang.String)) и передайте имя свойство документа, которое необходимо удалить.
{{% blocks/products/pf/feature-page-code %}}

```java
// load the SXC file using Workbook class
Workbook book = new Workbook("input.sxc");
// retrieve a list of all custom powerpointument properties of the Excel file
PowerpointumentPropertyCollection customProperties = workbook.getWorksheets().getCustomPowerpointumentProperties();
// remove a custom powerpointument property
customProperties.remove("Publisher"); 
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/sxc-to-powerpointx/" name="SXC К POWERPOINTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/sxc-to-powerpoint/" name="SXC К POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/sxc-to-word/" name="SXC К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/sxc-to-pptx/" name="SXC К PPTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}