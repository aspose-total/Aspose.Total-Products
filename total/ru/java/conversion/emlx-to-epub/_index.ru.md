---
title: Экспорт EMLX в EPUB через Java
description: Java API для преобразования EMLX в EPUB без использования Microsoft Word или Outlook
url_ignore: /ru/java/conversion/emlx-to-epub/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: EPUB
otherformats: PNG XPS FLATOPC MD TIFF DOTX EMF PDF DOTM EPUB RTF DOCM GIF TEXT SVG JPEG WORDML PS DOC DOT ODT OTT PCL DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API для рендеринга EMLX в EPUB" h2="Экспортируйте EMLX в EPUB с помощью локального Java API без использования каких-либо сторонних зависимостей." >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование электронной почты — это мощная функция, которую разработчики Java могут интегрировать в любые приложения Java J2SE, J2EE, J2ME через [Aspose.Total for Java](https://products.aspose.com/total/java/). Используя два API в пакете, вы можете преобразовать электронную почту EMLX в EPUB без каких-либо сторонних зависимостей. Во-первых, вы можете использовать API обработки электронной почты [Aspose.Email для Java](https://products.aspose.com/email/java/) для преобразования формата файла EMLX в HTML. Во-вторых, вы можете преобразовать HTML в EPUB с помощью API обработки документов [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать EMLX в EPUB" %}}
1. Откройте файл EMLX с помощью класса [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage).
2. Преобразуйте EMLX в HTML, используя [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions).)) метод
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате EPUB, используя [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions).)) и установите EPUB как SaveFormat
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