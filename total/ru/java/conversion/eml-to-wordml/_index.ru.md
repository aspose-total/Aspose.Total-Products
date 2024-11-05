---
title: Экспорт EML в WORDML через Java
description: Java API для преобразования EML в WORDML без использования Microsoft Word или Outlook
url_ignore: /ru/java/conversion/eml-to-wordml/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: WORD_ML
otherformats: DOT MD FLATOPC SVG GIF PCL DOCX JPEG PDF EPUB DOCM TEXT ODT RTF DOC WORDML OTT DOTM EMF XPS PNG PS DOTX TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API для рендеринга EML в WORDML" h2="Экспортируйте EML в WORDML с помощью локального Java API без использования каких-либо сторонних зависимостей." >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование электронной почты — это мощная функция, которую разработчики Java могут интегрировать в любые приложения Java J2SE, J2EE, J2ME через [Aspose.Total for Java](https://products.aspose.com/total/java/). Используя два API в пакете, вы можете преобразовать электронную почту EML в WORDML без каких-либо сторонних зависимостей. Во-первых, вы можете использовать API обработки электронной почты [Aspose.Email для Java](https://products.aspose.com/email/java/) для преобразования формата файла EML в HTML. Во-вторых, вы можете преобразовать HTML в WORDML с помощью API обработки документов [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать EML в WORDML" %}}
1. Откройте файл EML с помощью класса [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage).
2. Преобразуйте EML в HTML, используя [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions).)) метод
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
4. Сохраните документ в формате WORDML, используя [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions).)) и установите WORDML как SaveFormat
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