---
title: C# API для экспорта EPUB в PS
description: Преобразование EPUB в PS без использования Microsoft Word
url: /ru/net/conversion/epub-to-ps/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: PS
otherformats: WORDML DOTM XAMLFLOW MARKDOWN DOTX PS FLATOPC OTT PCL RTF DOT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг EPUB в PS через .NET" h2=".NET API для экспорта EPUB в PS в Windows, macOS и Linux без использования Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total для .NET](https://products.aspose.com/total/net/) — это мощный API для добавления функций обработки и преобразования документов в ваше приложение .NET. Используя расширенный API обработки PDF [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файлов EPUB в DOC. После этого, используя мощный API обработки документов [Aspose.Words для .NET](https://products.aspose.com/words/net/), вы можете преобразовать DOC в PS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования EPUB в PS" %}}
1. Откройте файл EPUB, используя класс [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте EPUB в Doc, используя метод [Сохранить](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл Doc с помощью класса [Document](https://apireference.aspose.com/words/net/aspose.words/document) Aspose.Words.
4. Сохраните документ в формате PS с помощью метода [Сохранить](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Ps как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("template.epub");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.ps", SaveFormat.Ps);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Расшифровать файл EPUB с помощью пароля владельца через .NET" %}}
Перед преобразованием EPUB в PS, если вы хотите расшифровать свой документ, вы можете сделать это с помощью API. Чтобы расшифровать файл PDF, сначала необходимо создать объект [Документ](https://apireference.aspose.com/pdf/net/aspose.pdf/document) и открыть EPUB, используя пароль владельца. После этого необходимо вызвать метод [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) объекта Document. Наконец, сохраните обновленный файл, используя метод Save объекта Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("Decrypt.epub", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать PS-файл только для чтения через .NET" %}}
Чтобы защитить ваш PS от редактирования и предотвратить редактирование важной и конфиденциальной информации в вашем документе другими людьми, вы также можете установить защиту документа с помощью API. Вы можете ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это можно сделать с помощью [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Это позволяет вам контролировать способ ограничения контента с помощью параметра перечисления [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.ps", SaveFormat.Ps);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-ott/" name="EPUB в OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-mhtml/" name="EPUB в MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-wordml/" name="EPUB в WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-dot/" name="EPUB в DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-odt/" name="EPUB в ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-rtf/" name="EPUB в RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-ps/" name="EPUB в PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-flatopc/" name="EPUB в FLAвPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-pcl/" name="EPUB в PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-markdown/" name="EPUB в MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-xamlflow/" name="EPUB в XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/epub-to-dotx/" name="EPUB в DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}