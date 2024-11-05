---
title: Экспорт OFT в XPS через Java
description: Java API для преобразования OFT в XPS без использования Microsoft Word или Outlook
url_ignore: /ru/java/conversion/oft-to-xps/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: XPS
otherformats: PNG TEXT PDF ODT PS DOT TIFF XPS MD FLATOPC RTF EMF PCL JPEG GIF OTT DOTX SVG DOCX DOCM DOTM EPUB WORDML DOC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API для рендеринга OFT в XPS" h2="Экспортируйте OFT в XPS с помощью локального Java API без использования каких-либо сторонних зависимостей." >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование электронной почты — это мощная функция, которую разработчики Java могут интегрировать в любые приложения Java J2SE, J2EE, J2ME через [Aspose.Total for Java](https://products.aspose.com/total/java/). Используя два API в пакете, вы можете преобразовать электронную почту OFT в XPS без каких-либо сторонних зависимостей. Во-первых, вы можете использовать API обработки электронной почты [Aspose.Oft для Java](https://products.aspose.com/email/java/) для преобразования формата файла OFT в HTML. Во-вторых, вы можете преобразовать HTML в XPS с помощью API обработки документов [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать OFT в XPS" %}}
1. Откройте файл OFT с помощью класса [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage).
2. Преобразуйте OFT в HTML, используя [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions).)) метод
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате XPS, используя [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions).)) и установите XPS как SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы должны использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}