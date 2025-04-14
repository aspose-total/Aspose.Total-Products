---
title: C# API для экспорта EMAIL в ODT
description: Преобразование EMAIL в ODT без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/email-to-odt/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: ODT
otherformats: OTT JPEG MD DOCM PCL EMF PS DOT DOCX TEXT PNG ODT DOC DOTM FLATOPC SVG PDF RTF TIFF EPUB DOTX XPS GIF WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EMAIL в ODT через .NET" h2=".NET API для преобразования электронной почты в ODT в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EMAIL в ODT в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла EMAIL в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в ODT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EMAIL в ODT" %}}
1. Откройте файл EMAIL с помощью класса [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage).
2. Преобразуйте EMAIL в HTML, используя метод [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате ODT с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Odt в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EMAIL через .NET" %}}
Перед преобразованием EMAIL в ODT, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EMAIL, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов ODT через .NET" %}}
При сохранении документа из EMAIL в ODT вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.odt", SaveFormat.Odt);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EMAIL в ODT: примеры использования" %}}
Преобразование файлов Email в формат ODT используется для хранения написанного контента, что делает их идеальным для создания формальных документов и презентаций. Однако при работе с данными мультимедийными OpenDocument Text файлы становятся необходимостью для визуализации и анализа документа.

Преобразование файлов Email в формат ODT позволяет раскрыть полную функциональность редактирования документов и создания презентаций. Это преобразование позволяет:

**Использованиям:**

*   **Создание формальных документов**: Преобразование Email в формат ODT используется для создания формальных отчетов, предложений и презентаций, что делает их идеальными для профессионального использования.
*   **Оптимизация корпоративной коммуникации**: Использование ODT позволяет визуализировать объявления компании, пресс-релизы и материалы маркетинга, оптимизируя внутреннюю и внешнюю коммуникацию.
*   **Научная работа и сотрудничество**: Преобразование Email в формат ODT используется для создания научных работ, эссе и тезисов, что упрощает сотрудничество между исследователями и учеными.
*   **Дigital Publishing and E-Learning**: Использование ODT позволяет форматировать образовательный контент, онлайн-курсы и цифровые публикации, делая обучение более интересным и доступным.
*   **Анализ данных с использованием документов**: Преобразование Email в формат ODT позволяет извлекать данные из написанного текста, выявлять тенденции и отслеживать изменения в коммуникации компании.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}