---
title: C# API для экспорта EMAIL в PDF
description: Преобразование EMAIL в PDF без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/email-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: OTT DOT MD ODT TEXT PCL PS SVG DOCX DOTM DOCM JPEG RTF FLATOPC PNG XPS WORDML PDF EPUB DOC EMF DOTX TIFF GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EMAIL в PDF через .NET" h2=".NET API для преобразования электронной почты в PDF в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EMAIL в PDF в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EMAIL в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в PDF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EMAIL в PDF" %}}
1. Откройте файл EMAIL с помощью класса [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Преобразуйте EMAIL в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате PDF с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Pdf в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-pdf.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EMAIL через .NET" %}}
Перед преобразованием EMAIL в PDF, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EMAIL, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов PDF через .NET" %}}
При сохранении документа из EMAIL в PDF вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EMAIL в PDF: примеры использования" %}}
Переведение файлов из электронной почты в форматы PDF позволяет использовать полную функциональность возможностей управления документами. Это особенно важно для:

**Использование документов:**

* **Официальные документы и соответствие требованиям**: Переведение файлов в формат PDF помогает сохранять официальные записи, соблюдать регуляции и упрощать проверку.

* **Рекламационные материалы и кампании по продвижу**: Использование PDF позволяет создавать готовые к печати рекламационные материалы, буклеты и кампании, которые эффективно отражают образ компании.

* **Тренинги и учебные материалы**: Переведение файлов в формат PDF помогает создать интерактивные обучающие руководства, материалы для курсов и пособники для студентов или сотрудников.

* **Прложения и контракты**: Создание профессионально выглядящих прложений и контрактов в формате PDF позволяет четко передать сообщение и обеспечить безопасность.

* **Художественные и творческие проекты**: Переведение файлов в формат PDF помогает сохранять цифровое искусство, изображения или дизайны, подготавливая их к печати или для отправки клиентам.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}