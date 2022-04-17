---
title: C# API для экспорта OFT в DOTM
description: Преобразование OFT в DOTM без использования Microsoft Word или Outlook на .NET
url: /ru/net/conversion/oft-to-dotm/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: DOTM
otherformats: ODT PS DOTM RTF PCL TEXT DOT SVG DOTX OTT MD DOCX DOCM EPUB WORDML EMF PNG TIFF FLATOPC JPEG PDF DOC XPS GIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт OFT в DOTM через .NET" h2=".NET API для преобразования электронной почты в DOTM в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования OFT в DOTM в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Oft для .NET](https://products.aspose.com/oft/net/), вы можете преобразовать формат файла OFT в HTML. После этого, используя [Aspose.Words для .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в DOTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования OFT в DOTM" %}}
1. Откройте файл OFT с помощью класса [MailMessage](https://apireference.aspose.com/oft/net/aspose.oft/mailmessage).
2. Преобразуйте OFT в HTML, используя метод [Сохранить](https://apireference.aspose.com/oft/net/aspose.oft.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://apireference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате DOTM с помощью метода [Сохранить] (https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Dotm в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
// load the OFT file to be converted
MailMessage message = MailMessage.Load("sourceFile.msg");
// save OFT as a HTML 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.Dotm
document.Save("output.dotm", SaveFormat.Dotm); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл OFT через .NET" %}}
Перед преобразованием OFT в DOTM, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ OFT, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://apireference.aspose.com/oft/net/aspose.oft.mapi/mapimessage) класса [Aspose.Oft для .NET](https://products.aspose.com/oft /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://apireference.aspose.com/oft/net/aspose.oft.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs
// instantiate MapiMessage to load an MSG file from disk
var outlookMessageFile = MapiMessage.FromFile("message.msg");
// check for SenderName 
if(outlookMessageFile.SenderName == "John"){
    //proceed with conversion process
}
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов DOTM через .NET" %}}
При сохранении документа из OFT в DOTM вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// apply document protection and set protection password
doc.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Dotm
document.Save("output.dotm", SaveFormat.Dotm);  
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-pcl/" name="MSG в PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-pdf/" name="MSG в PDF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-dot/" name="MSG в DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-flatopc/" name="MSG в FLAвPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-jpeg/" name="MSG в JPEG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-png/" name="MSG в PNG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-rtf/" name="MSG в RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-tiff/" name="MSG в TIFF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-docm/" name="MSG в DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-ps/" name="MSG в PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-gif/" name="MSG в GIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-xps/" name="MSG в XPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-odt/" name="MSG в ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-docx/" name="MSG в DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-doc/" name="MSG в DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-wordml/" name="MSG в WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-svg/" name="MSG в SVG" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-epub/" name="MSG в EPUB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-md/" name="MSG в MD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-emf/" name="MSG в EMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-dotm/" name="MSG в DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-ott/" name="MSG в OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-dotx/" name="MSG в DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/msg-to-text/" name="MSG в TEXT" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}