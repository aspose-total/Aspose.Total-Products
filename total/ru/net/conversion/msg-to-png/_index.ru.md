---
title: C# API для экспорта MSG в PNG
description: Преобразование MSG в PNG без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/msg-to-png/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PNG
otherformats: DOCX XPS WORDML DOT SVG TIFF OTT ODT EMF FLATOPC EPUB DOC GIF TEXT MD PDF DOTX PNG RTF PCL PS DOCM JPEG DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт MSG в PNG через .NET" h2=".NET API для преобразования электронной почты в PNG в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования MSG в PNG в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла MSG в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в PNG.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования MSG в PNG" %}}
1. Откройте файл MSG с помощью класса [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage).
2. Преобразуйте MSG в HTML, используя метод [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате PNG с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Png в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл MSG через .NET" %}}
Перед преобразованием MSG в PNG, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ MSG, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов PNG через .NET" %}}
При сохранении документа из MSG в PNG вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.png", SaveFormat.Png);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла MSG в PNG: примеры использования" %}}
ФайлыMSG (Message)используются дляхранения текстовых сообщений, что делает их идеальным форматом для передачи и приема текстовой данных. Однако при работе со визуальными данными, такие как изображенияPNG, становятсянеобходимыми для создания статических графиков и иллюстраций.

Преобразование файловMSGв форматыPNG позволяет раскрыть полную функциональность вашей возможностивизуализации и анализировани. Это позволит вам:

**Использования:**

*   **Социальное媒体долявливание**: Преобразовать файлыMSG для передачи сообщений на социальных сетях, таких как Facebook, Twitter или Instagram, добавив визуальные элементы, такие как изображения или видео.
*   **Текстовоеобразиеизображение**: ИспользоватьPNG для生成а изображений из текстового ввода, создавая привлекательные графики для презентаций, отчетов или материалов для маркетинга.
*   **Интеграциячатботов**: Преобразовать файлыMSG для интеграциичатботов с приложениями для сообщений, позволяя пользователям взаимодействовать со ботами и получать визуальные данные, такие как изображения или видео.
*   **Документ生成**: ИспользоватьPNG для создания интерактивных документов с визуальными элементами, такими как диаграммы, инфографики или скриншоты, что упрощает понимание сложной информации пользователями.
*   **Дизайн电子обновлений**: Преобразовать файлыMSG для создания привлекательных email-новостей с изображениями, текстом и другими многомедийными элементами, что повышает уровень вовлечения пользователей и конверсию.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}