---
title: C# API для экспорта MSG в PDF
description: Преобразование MSG в PDF без использования Microsoft Word или Outlook на .NET
url_ignore: /ru/net/conversion/msg-to-pdf/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: PDF
otherformats: DOT ODT WORDML JPEG PCL EMF TEXT RTF EPUB FLATOPC PDF SVG GIF OTT PS DOCX MD TIFF DOTM PNG DOCM XPS DOC DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт MSG в PDF через .NET" h2=".NET API для преобразования электронной почты в PDF в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования MSG в PDF в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Email for .NET](https://products.aspose.com/email/net/), вы можете преобразовать формат файла MSG в HTML. После этого, используя [Aspose.Words for .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в PDF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования MSG в PDF" %}}
1. Откройте файл MSG с помощью класса [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage).
2. Преобразуйте MSG в HTML, используя метод [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3).
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

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл MSG через .NET" %}}
Перед преобразованием MSG в PDF, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ MSG, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) класса [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов PDF через .NET" %}}
При сохранении документа из MSG в PDF вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pdf", SaveFormat.Pdf);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла MSG в PDF: примеры использования" %}}
Переведение файлов сообщений (MSG) в формат портального документа (PDF) является необходимым шагом для раскрытия полной функциональности вашего документа. Это позволит:

**Использования:**

*   **Конformance отчетность**: Переведение файлов MSG в формат PDF для соответствия регуляциям, чтобы предоставлять точные и вовремя поданные документы.
*   **Архивирование документов**: Использование преобразования в PDF для сохранения исторических сообщений и записей, что делает их доступными для будущего сбора данных или анализа.
*   **Проверка выборов**: Переведение файлов MSG в формат PDF для процессов проверки выборов, чтобы обеспечить целостность данных о голосах.
*   **Застрая интеллектуальной собственности**: Использование преобразования в PDF для защиты конфиденциальных данных бизнеса, превращая секретные документы в форму, которая позволяет выявлять подделки.
*   **Управление архивом данных**: Переведение файлов MSG в формат PDF для хранения исторических данных, что делает их легко доступными для будущего анализа или отчета.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}