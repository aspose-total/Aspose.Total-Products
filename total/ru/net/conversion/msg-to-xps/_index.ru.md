---
title: C# API для экспорта MSG в XPS
description: Преобразование MSG в XPS без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/msg-to-xps/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: XPS
otherformats: DOC XPS DOCX WORDML GIF PCL SVG EMF JPEG EPUB DOTM DOTX OTT RTF ODT DOT TIFF DOCM TEXT PS PNG MD PDF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт MSG в XPS через .NET" h2=".NET API для преобразования электронной почты в XPS в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования MSG в XPS в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла MSG в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования MSG в XPS" %}}
1. Откройте файл MSG с помощью класса [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage).
2. Преобразуйте MSG в HTML, используя метод [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://reference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате XPS с помощью метода [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Xps в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл MSG через .NET" %}}
Перед преобразованием MSG в XPS, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ MSG, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов XPS через .NET" %}}
При сохранении документа из MSG в XPS вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла MSG в XPS: примеры использования" %}}
Переведение файлов MSG в форматы XPS позволяет раскрыть полную функциональность возможностей редактирования и управления документами. Это особенно важно для:

**Использование случаев:**

*   **Редактирование документов:** Переведение файлов MSG в форматы XPS позволяет редактировать документы, добавлять новую информацию и изменять существующая данные.
*   **Захисление сообщений:** Использование форматов XPS помогает сохранить сообщения, обеспечить целостность данных и предотвратить их повредление.
*   **Безопасность файлов:** Переведение MSG в XPS позволяет зашифровать чувствительные данные и защитить их от несанкционированного доступа.
*   **Улучшение совместимости:** Форматы XPS позволяют создавать документы, которые совместимы с разными платформами, обеспечивая гладкую 共作vie.
*   **Архивирование данных:** Переведение файлов MSG в форматы XPS позволяет архивировать данные, хранить историческую информацию и сохранять записи прошлых коммуникаций.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}