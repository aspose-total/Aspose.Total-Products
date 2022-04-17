---
title: C# API для экспорта EML в OTT
description: Преобразование EML в OTT без использования Microsoft Word или Outlook на .NET
url: /ru/net/conversion/eml-to-ott/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: OTT
otherformats: EPUB TEXT MD WORDML ODT GIF EMF SVG DOCX PCL DOTM FLATOPC DOC PS PDF XPS RTF DOCM DOT TIFF DOTX OTT PNG JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Экспорт EML в OTT через .NET" h2=".NET API для преобразования электронной почты в OTT в Windows, macOS и Linux без использования Word или Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Если вы являетесь разработчиком .NET и хотите добавить функции преобразования EML в OTT в свои приложения, API-интерфейсы для работы с форматами файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/) — это то, что вам нужно. вперед. Используя [Aspose.Eml для .NET](https://products.aspose.com/eml/net/), вы можете преобразовать формат файла EML в HTML. После этого, используя [Aspose.Words для .NET](https://products.aspose.com/words/net/), вы можете преобразовать HTML в OTT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EML в OTT" %}}
1. Откройте файл EML с помощью класса [MailMessage](https://apireference.aspose.com/eml/net/aspose.eml/mailmessage).
2. Преобразуйте EML в HTML, используя метод [Сохранить](https://apireference.aspose.com/eml/net/aspose.eml.mailmessage/save/methods/3).
3. Загрузите HTML с помощью класса [Document](https://apireference.aspose.com/words/net/aspose.words/document).
4. Сохраните документ в формате OTT с помощью метода [Сохранить] (https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Ott в качестве формата сохранения.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.ott", SaveFormat.Ott); 
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Разобрать файл EML через .NET" %}}
Перед преобразованием EML в OTT, если вы хотите убедиться, что конвертируете правильное электронное письмо, вы можете загрузить документ EML, проанализировать его и просмотреть желаемое свойство. Используя класс [MapiMessage](https://apireference.aspose.com/eml/net/aspose.eml.mapi/mapimessage) класса [Aspose.Eml для .NET](https://products.aspose.com/eml /net/) API, вы можете получить информацию об отправителе и получателе. Например, вы можете проверить адрес электронной почты отправителя для конверсии, используя свойство [SenderName](https://apireference.aspose.com/eml/net/aspose.eml.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Ограничить редактирование документов OTT через .NET" %}}
При сохранении документа из EML в OTT вам может потребоваться защитить выходной документ. Иногда вам может понадобиться ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это может быть полезно, чтобы другие люди не могли редактировать важную и конфиденциальную информацию в вашем документе. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API позволяет вам контролировать способ ограничения контента с помощью [ProtectionType](https://apireference.aspose. com/words/net/aspose.words/protectiontype) параметр перечисления. Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ott", SaveFormat.Ott);  
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