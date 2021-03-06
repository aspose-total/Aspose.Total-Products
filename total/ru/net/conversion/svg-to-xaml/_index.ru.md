---
title: Экспорт SVG в XAML через C# API
description: .NET API для преобразования SVG в XAML без использования Microsoft Word
url_ignore: /ru/net/conversion/svg-to-xaml/
family: total
platformtag: net
feature: conversion
informat: SVG
outformat: XAML
otherformats: PPT PPSM SWF XAML POWERPOINT OTP PPTM PPSX POTX PPS POTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг SVG в XAML через .NET" h2=".NET API для экспорта SVG в XAML в Windows, macOS и Linux без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя пакет мощных API-интерфейсов автоматизации форматов файлов [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете легко преобразовать SVG в XAML, выполнив два простых шага. Используя API обработки PDF [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файла SVG в PPTX. После этого с помощью API обработки презентаций [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) вы можете конвертировать PPTX в XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования SVG в XAML" %}}
1. Откройте файл SVG, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте SVG в PPTX, используя метод [Сохранить](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл PPTX с помощью класса [Презентация](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Сохраните документ в формате XAML с помощью метода [Сохранить](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) и установите «Xaml» в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.svg");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.xaml", SaveFormat.Xaml);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить метаданные XMP из файла SVG через .NET" %}}
При преобразовании SVG в XAML вам может понадобиться дополнительная информация о метаданных XMP, чтобы определить приоритетность процесса пакетного преобразования. Например, вы можете получать и сортировать документы преобразования по дате создания и соответствующим образом обрабатывать документы. [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/) позволяет получить доступ к метаданным XMP файла SVG. Чтобы получить метаданные файла SVG, вы можете создать объект [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document) и открыть входной файл SVG. После этого вы можете получить метаданные файла с помощью свойства [Метаданные](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs
Document doc = new Document("input.svg");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать файл XAML только для чтения через .NET" %}}
Используя API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), вы можете еще больше расширить возможности своего приложения для преобразования. Одной из функций может быть создание выходного файла только для чтения для повышения безопасности. API позволяет настроить файл XAML только для чтения, что означает, что пользователи (после того, как они откроют презентацию) увидят рекомендацию только для чтения. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-pot/" name="SVG в POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-ppsx/" name="SVG в PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-swf/" name="SVG в SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-powerpoint/" name="SVG в POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-otp/" name="SVG в OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-potm/" name="SVG в POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-ppt/" name="SVG в PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-pps/" name="SVG в PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-potx/" name="SVG в POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-xaml/" name="SVG в XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-ppsm/" name="SVG в PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/svg-to-pptm/" name="SVG в PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}