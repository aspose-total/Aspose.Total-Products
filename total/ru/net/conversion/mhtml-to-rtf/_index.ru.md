---
title: C# API для экспорта MHTML в RTF
description: Преобразование MHTML в RTF без использования Microsoft Word
url: /ru/net/conversion/mhtml-to-rtf/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: RTF
otherformats: DOTM PS WORDML DOT DOTX ODT RTF OTT MARKDOWN XAMLFLOW PCL FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг MHTML в RTF через .NET" h2=".NET API для экспорта MHTML в RTF в Windows, macOS и Linux без использования Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total для .NET](https://products.aspose.com/total/net/) — это мощный API для добавления функций обработки и преобразования документов в ваше приложение .NET. Используя расширенный API обработки PDF [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файлов MHTML в DOC. После этого, используя мощный API обработки документов [Aspose.Words для .NET](https://products.aspose.com/words/net/), вы можете преобразовать DOC в RTF.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования MHTML в RTF" %}}
1. Откройте файл MHTML, используя класс [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте MHTML в Doc, используя метод [Сохранить](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл Doc с помощью класса [Document](https://apireference.aspose.com/words/net/aspose.words/document) Aspose.Words.
4. Сохраните документ в формате RTF с помощью метода [Сохранить](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Rtf как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("template.mhtml");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.rtf", SaveFormat.Rtf);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Расшифровать файл MHTML с помощью пароля владельца через .NET" %}}
Перед преобразованием MHTML в RTF, если вы хотите расшифровать свой документ, вы можете сделать это с помощью API. Чтобы расшифровать файл PDF, сначала необходимо создать объект [Документ](https://apireference.aspose.com/pdf/net/aspose.pdf/document) и открыть MHTML, используя пароль владельца. После этого необходимо вызвать метод [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) объекта Document. Наконец, сохраните обновленный файл, используя метод Save объекта Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("Decrypt.mhtml", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать RTF-файл только для чтения через .NET" %}}
Чтобы защитить ваш RTF от редактирования и предотвратить редактирование важной и конфиденциальной информации в вашем документе другими людьми, вы также можете установить защиту документа с помощью API. Вы можете ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это можно сделать с помощью [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Это позволяет вам контролировать способ ограничения контента с помощью параметра перечисления [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.rtf", SaveFormat.Rtf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-ott/" name="MHTML в OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-mhtml/" name="MHTML в MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-wordml/" name="MHTML в WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-dot/" name="MHTML в DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-odt/" name="MHTML в ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-rtf/" name="MHTML в RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-ps/" name="MHTML в PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-flatopc/" name="MHTML в FLAвPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-pcl/" name="MHTML в PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-markdown/" name="MHTML в MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-xamlflow/" name="MHTML в XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/mhtml-to-dotx/" name="MHTML в DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}