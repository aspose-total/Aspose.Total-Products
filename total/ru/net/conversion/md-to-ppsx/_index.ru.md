---
title: Экспорт MD в PPSX через C# API
description: .NET API для преобразования MD в PPSX без использования Microsoft Word
url_ignore: /ru/net/conversion/md-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: PPSX
otherformats: PPSX POWERPOINT SWF POTX OTP PPSM PPT XAML PPS PPTM POT POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг MD в PPSX через .NET" h2=".NET API для экспорта MD в PPSX в Windows, macOS и Linux без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя пакет мощных API-интерфейсов автоматизации форматов файлов [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете легко преобразовать MD в PPSX, выполнив два простых шага. Используя API обработки PDF [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файла MD в PPTX. После этого с помощью API обработки презентаций [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) вы можете конвертировать PPTX в PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования MD в PPSX" %}}
1. Откройте файл MD, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте MD в PPTX, используя метод [Сохранить](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл PPTX с помощью класса [Презентация](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Сохраните документ в формате PPSX с помощью метода [Сохранить](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) и установите «Ppsx» в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.md");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.ppsx", SaveFormat.Ppsx);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить метаданные XMP из файла MD через .NET" %}}
При преобразовании MD в PPSX вам может понадобиться дополнительная информация о метаданных XMP, чтобы определить приоритетность процесса пакетного преобразования. Например, вы можете получать и сортировать документы преобразования по дате создания и соответствующим образом обрабатывать документы. [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/) позволяет получить доступ к метаданным XMP файла MD. Чтобы получить метаданные файла MD, вы можете создать объект [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document) и открыть входной файл MD. После этого вы можете получить метаданные файла с помощью свойства [Метаданные](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs
Document doc = new Document("input.md");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать файл PPSX только для чтения через .NET" %}}
Используя API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), вы можете еще больше расширить возможности своего приложения для преобразования. Одной из функций может быть создание выходного файла только для чтения для повышения безопасности. API позволяет настроить файл PPSX только для чтения, что означает, что пользователи (после того, как они откроют презентацию) увидят рекомендацию только для чтения. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsx", SaveFormat.Ppsx);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-pot/" name="MD в POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-ppsx/" name="MD в PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-swf/" name="MD в SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-powerpoint/" name="MD в POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-otp/" name="MD в OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-potm/" name="MD в POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-ppt/" name="MD в PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-pps/" name="MD в PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-potx/" name="MD в POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-xaml/" name="MD в XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-ppsm/" name="MD в PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/md-to-pptm/" name="MD в PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}