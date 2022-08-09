---
title: Преобразование EMLX в TIFF в приложении Andorid
description: Экспорт EMLX в TIFF без использования Microsoft Word или Outlook в ваших приложениях Andorid.
url: /ru/android-java/conversion/emlx-to-tiff/
family: total
platformtag: cpp
feature: conversion
informat: EMLX
outformat: TIFF
otherformats: WORDML XPS DOTX DOCX TEXT PNG SVG DOT DOC MD JPEG DOCM ODT EPUB PS PDF EMF RTF FLATOPC OTT PCL DOTM BMP GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование EMLX в TIFF в приложениях Andorid" h2="Разработка приложений Andorid для экспорта EMLX в TIFF с использованием Andorid через Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Приложения Andorid просты в ежедневном использовании конечными пользователями. День ото дня количество пользователей телефонов Andorid растет. Используя мощные библиотеки автоматизации форматов файлов [Aspose.Total для Android через Java](https://products.aspose.com/total/android-java/), вы можете разрабатывать приложения для обработки и преобразования электронной почты. Вы можете конвертировать EMLX в TIFF с помощью комбинации [Aspose.Emlx для Android Java](https://products.aspose.com/emlx/android-java/) и [Aspose.Words для Andorid Java](https://products.aspose.com/words/android-java/). С помощью первого API вы можете конвертировать формат файла EMLX в HTML, а с помощью второго API вы можете отображать HTML как TIFF. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертировать EMLX в TIFF в Andorid" %}}
1. Откройте файл EMLX с помощью класса [MailMessage](https://reference.aspose.com/emlx/java/com.aspose.emlx/mailmessage).
2. Преобразуйте EMLX в HTML, используя [save](https://reference.aspose.com/emlx/java/com.aspose.emlx/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions). )) метод
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате TIFF, используя [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions). )) и установите TIFF как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Android через Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.Emlx для Android через Java](https://docs.aspose.com/emlx/androidjava/installation/) и [Aspose.Words для Android через Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-через-java/#install-asposewords-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EMLX file to be converted
MailMessage message = MailMessage.load("sourceFile.emlx"); 
// save EMLX as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.TIFF
document.save("output.tiff", SaveFormat.TIFF); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-wordml/" name="EMLX К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-xps/" name="EMLX К XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-dotx/" name="EMLX К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-docx/" name="EMLX К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-text/" name="EMLX К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-png/" name="EMLX К PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-svg/" name="EMLX К SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-dot/" name="EMLX К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-doc/" name="EMLX К DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-md/" name="EMLX К MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-jpeg/" name="EMLX К JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-docm/" name="EMLX К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-odt/" name="EMLX К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-epub/" name="EMLX К EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-ps/" name="EMLX К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-pdf/" name="EMLX К PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-emf/" name="EMLX К EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-rtf/" name="EMLX К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-flatopc/" name="EMLX К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-ott/" name="EMLX К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-pcl/" name="EMLX К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-dotm/" name="EMLX К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-tiff/" name="EMLX К TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/emlx-to-gif/" name="EMLX К GIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}