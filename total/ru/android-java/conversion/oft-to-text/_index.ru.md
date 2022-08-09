---
title: Преобразование OFT в TEXT в приложении Andorid
description: Экспорт OFT в TEXT без использования Microsoft Word или Outlook в ваших приложениях Andorid.
url: /ru/android-java/conversion/oft-to-text/
family: total
platformtag: cpp
feature: conversion
informat: OFT
outformat: TEXT
otherformats: DOT ODT DOC SVG XPS BMP PNG TIFF OTT RTF PCL EMF MD WORDML DOCX GIF FLATOPC DOCM DOTX PDF EPUB DOTM PS JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование OFT в TEXT в приложениях Andorid" h2="Разработка приложений Andorid для экспорта OFT в TEXT с использованием Andorid через Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Приложения Andorid просты в ежедневном использовании конечными пользователями. День ото дня количество пользователей телефонов Andorid растет. Используя мощные библиотеки автоматизации форматов файлов [Aspose.Total для Android через Java](https://products.aspose.com/total/android-java/), вы можете разрабатывать приложения для обработки и преобразования электронной почты. Вы можете конвертировать OFT в TEXT с помощью комбинации [Aspose.Oft для Android Java](https://products.aspose.com/oft/android-java/) и [Aspose.Words для Andorid Java](https://products.aspose.com/words/android-java/). С помощью первого API вы можете конвертировать формат файла OFT в HTML, а с помощью второго API вы можете отображать HTML как TEXT. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертировать OFT в TEXT в Andorid" %}}
1. Откройте файл OFT с помощью класса [MailMessage](https://reference.aspose.com/oft/java/com.aspose.oft/mailmessage).
2. Преобразуйте OFT в HTML, используя [save](https://reference.aspose.com/oft/java/com.aspose.oft/MailMessage#save(java.io.OutputStream,%20com.aspose.oft.SaveOptions). )) метод
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате TEXT, используя [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions). )) и установите TEXT как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.Oft для Android через Java](https://docs.aspose.com/oft/androidjava/installation/) и [Aspose.Words для Android через Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-через-java/#install-asposewords-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.TEXT
document.save("output.text", SaveFormat.TEXT); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-dot/" name="OFT К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-odt/" name="OFT К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-doc/" name="OFT К DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-svg/" name="OFT К SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-xps/" name="OFT К XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-text/" name="OFT К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-png/" name="OFT К PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-tiff/" name="OFT К TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-ott/" name="OFT К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-rtf/" name="OFT К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-pcl/" name="OFT К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-emf/" name="OFT К EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-md/" name="OFT К MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-wordml/" name="OFT К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-docx/" name="OFT К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-gif/" name="OFT К GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-flatopc/" name="OFT К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-docm/" name="OFT К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-dotx/" name="OFT К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-pdf/" name="OFT К PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-epub/" name="OFT К EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-dotm/" name="OFT К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-ps/" name="OFT К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/oft-to-jpeg/" name="OFT К JPEG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}