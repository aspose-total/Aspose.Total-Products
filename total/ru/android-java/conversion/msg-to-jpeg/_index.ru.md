---
title: Преобразование MSG в JPEG в приложении Andorid
description: Экспорт MSG в JPEG без использования Microsoft Word или Outlook в ваших приложениях Andorid.

family: total
platformtag: cpp
feature: conversion
informat: MSG
outformat: JPEG
otherformats: PDF PCL BMP RTF PNG DOC XPS SVG WORDML ODT DOTX TIFF OTT DOCX PS DOCM GIF FLATOPC DOT EMF DOTM EPUB MD TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование MSG в JPEG в приложениях Andorid" h2="Разработка приложений Andorid для экспорта MSG в JPEG с использованием Andorid через Java API" >}}

{{% blocks/products/pf/feature-page-summary %}}
Приложения Andorid просты в ежедневном использовании конечными пользователями. День ото дня количество пользователей телефонов Andorid растет. Используя мощные библиотеки автоматизации форматов файлов [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/), вы можете разрабатывать приложения для обработки и преобразования электронной почты. Вы можете конвертировать MSG в JPEG с помощью комбинации [Aspose.Msg для Android Java](https://products.aspose.com/msg/android-java/) и [Aspose.Words для Andorid Java](https://products.aspose.com/words/android-java/). С помощью первого API вы можете конвертировать формат файла MSG в HTML, а с помощью второго API вы можете отображать HTML как JPEG. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Конвертировать MSG в JPEG в Andorid" %}}
1. Откройте файл MSG с помощью класса [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage).
2. Преобразуйте MSG в HTML, используя [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.msg.SaveOptions). )) метод
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате JPEG, используя [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions). )) и установите JPEG как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://releases.aspose.com/total/java/) и установите [Aspose.Msg для Android через Java](https://docs.aspose.com/msg/androidjava/installation/) и [Aspose.Words for Android via Java](https://docs.aspose.com/words/java/install-aspose-words-for-android-через-java/#install-asposewords-for-android-через-java-из-maven-репозитория) в ваших приложениях.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the MSG file to be converted
MailMessage message = MailMessage.load("sourceFile.msg"); 
// save MSG as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.JPEG
document.save("output.jpeg", SaveFormat.JPEG); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}