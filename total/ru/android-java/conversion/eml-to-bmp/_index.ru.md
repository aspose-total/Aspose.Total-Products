---
title: Преобразование EML в BMP в приложении Andorid
description: Экспорт EML в BMP без использования Microsoft Word или Outlook в ваших приложениях Andorid.
url: /ru/android-java/conversion/eml-to-bmp/
family: total
platformtag: cpp
feature: conversion
informat: EML
outformat: BMP
otherformats: PDF TIFF ODT DOTX WORDML DOCX TEXT RTF DOTM EMF DOC OTT FLATOPC PNG EPUB DOCM PCL JPEG MD GIF DOT XPS PS SVG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование EML в BMP в приложениях Andorid" h2="Разработка приложений Andorid для экспорта EML в BMP с использованием Andorid через Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Приложения Andorid просты в ежедневном использовании конечными пользователями. День ото дня количество пользователей телефонов Andorid растет. Используя мощные библиотеки автоматизации форматов файлов [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), вы можете разрабатывать приложения для обработки и преобразования электронной почты. Вы можете конвертировать EML в BMP с помощью комбинации [Aspose.Eml для Android Java](https://products.aspose.com/eml/android-java/) и [Aspose.Words для Andorid Java](https://products.aspose.com/words/android-java/). С помощью первого API вы можете конвертировать формат файла EML в HTML, а с помощью второго API вы можете отображать HTML как BMP. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертировать EML в BMP в Andorid" %}}
1. Откройте файл EML с помощью класса [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage).
2. Преобразуйте EML в HTML, используя [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions). )) метод
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате BMP, используя [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions). )) и установите BMP как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) и установите [Aspose.Eml для Android через Java](https://docs.aspose.com/eml/androidjava/installation/) и [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-через-java/#install-asposewords-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the EML file to be converted
MailMessage message = MailMessage.load("sourceFile.eml"); 
// save EML as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.BMP
document.save("output.bmp", SaveFormat.BMP); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие поддерживаемые преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-pdf/" name="EML К PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-tiff/" name="EML К TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-odt/" name="EML К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-dotx/" name="EML К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-wordml/" name="EML К WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-docx/" name="EML К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-text/" name="EML К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-rtf/" name="EML К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-dotm/" name="EML К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-emf/" name="EML К EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-doc/" name="EML К DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-ott/" name="EML К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-flatopc/" name="EML К FLATOPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-png/" name="EML К PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-epub/" name="EML К EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-docm/" name="EML К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-pcl/" name="EML К PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-jpeg/" name="EML К JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-md/" name="EML К MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-gif/" name="EML К GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-dot/" name="EML К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-xps/" name="EML К XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-ps/" name="EML К PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/android-java/conversion/eml-to-svg/" name="EML К SVG" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}