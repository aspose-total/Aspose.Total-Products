---
title: C# API для экспорта MD в PCL
description: Преобразование MD в PCL без использования Microsoft Word
url: /ru/net/conversion/md-to-pcl/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: PCL
otherformats: OTT PS DOT DOTX WORDML PCL MARKDOWN RTF FLATOPC XAMLFLOW MHTML DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг MD в PCL через .NET" h2=".NET API для экспорта MD в PCL в Windows, macOS и Linux без использования Microsoft Word" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total для .NET](https://products.aspose.com/total/net/) — это мощный API для добавления функций обработки и преобразования документов в ваше приложение .NET. Используя расширенный API обработки PDF [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файлов MD в DOC. После этого, используя мощный API обработки документов [Aspose.Words для .NET](https://products.aspose.com/words/net/), вы можете преобразовать DOC в PCL.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C# API для преобразования MD в PCL" %}}
1. Откройте файл MD, используя класс [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте MD в Doc, используя метод [Сохранить](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл Doc с помощью класса [Document](https://apireference.aspose.com/words/net/aspose.words/document) Aspose.Words.
4. Сохраните документ в формате PCL с помощью метода [Сохранить](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) и установите Pcl как SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("template.md");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.pcl", SaveFormat.Pcl);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Расшифровать файл MD с помощью пароля владельца через .NET" %}}
Перед преобразованием MD в PCL, если вы хотите расшифровать свой документ, вы можете сделать это с помощью API. Чтобы расшифровать файл PDF, сначала необходимо создать объект [Документ](https://apireference.aspose.com/pdf/net/aspose.pdf/document) и открыть MD, используя пароль владельца. После этого необходимо вызвать метод [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) объекта Document. Наконец, сохраните обновленный файл, используя метод Save объекта Document.  
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("Decrypt.md", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать PCL-файл только для чтения через .NET" %}}
Чтобы защитить ваш PCL от редактирования и предотвратить редактирование важной и конфиденциальной информации в вашем документе другими людьми, вы также можете установить защиту документа с помощью API. Вы можете ограничить возможность редактирования документа и разрешить только определенные действия с ним. Это можно сделать с помощью [Aspose.Words for .NET](https://products.aspose.com/words/net/) API. Это позволяет вам контролировать способ ограничения контента с помощью параметра перечисления [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype). Вы можете сделать свой документ доступным только для чтения, используя следующие строки кода. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.doc");

doc.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-ott/" name="MD в OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-mhtml/" name="MD в MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-wordml/" name="MD в WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-dot/" name="MD в DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-odt/" name="MD в ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-rtf/" name="MD в RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-ps/" name="MD в PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-flatopc/" name="MD в FLAвPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-pcl/" name="MD в PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-markdown/" name="MD в MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-xamlflow/" name="MD в XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-dotx/" name="MD в DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}