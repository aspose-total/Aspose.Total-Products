---
title: Экспорт XSLFO в PPSM через C# API
description: .NET API для преобразования XSLFO в PPSM без использования Microsoft Word
url: /ru/net/conversion/xslfo-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: XSLFO
outformat: PPSM
otherformats: PPSM PPSX POTX POT POWERPOINT PPS PPTM XAML OTP PPT SWF POTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг XSLFO в PPSM через .NET" h2=".NET API для экспорта XSLFO в PPSM в Windows, macOS и Linux без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя пакет мощных API-интерфейсов автоматизации форматов файлов [Aspose.Total для .NET](https://products.aspose.com/total/net/), вы можете легко преобразовать XSLFO в PPSM, выполнив два простых шага. Используя API обработки PDF [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файла XSLFO в PPTX. После этого с помощью API обработки презентаций [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) вы можете конвертировать PPTX в PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования XSLFO в PPSM" %}}
1. Откройте файл XSLFO, используя класс [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте XSLFO в PPTX, используя метод [Сохранить](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл PPTX с помощью класса [Презентация](https://apireference.aspose.com/slides/net/aspose.slides/presentation).
4. Сохраните документ в формате PPSM с помощью метода [Сохранить](https://apireference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) и установите «Ppsm» в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://downloads.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs
Document document = new Document("input.xslfo");
 
document.Save("PptxOutput.pptx", SaveFormat.Pptx); 

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.Save("output.ppsm", SaveFormat.Ppsm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить метаданные XMP из файла XSLFO через .NET" %}}
При преобразовании XSLFO в PPSM вам может понадобиться дополнительная информация о метаданных XMP, чтобы определить приоритетность процесса пакетного преобразования. Например, вы можете получать и сортировать документы преобразования по дате создания и соответствующим образом обрабатывать документы. [Aspose.PDF для .NET](https://products.aspose.com/pdf/net/) позволяет получить доступ к метаданным XMP файла XSLFO. Чтобы получить метаданные файла XSLFO, вы можете создать объект [Документ](https://apireference.aspose.com/pdf/net/aspose.pdf/document) и открыть входной файл XSLFO. После этого вы можете получить метаданные файла с помощью свойства [Метаданные](https://apireference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}

```cs
Document doc = new Document("input.xslfo");

Console.WriteLine(doc.Metadata["xmp:CreateDate"]);
Console.WriteLine(doc.Metadata["xmp:Nickname"]);
Console.WriteLine(doc.Metadata["xmp:CustomProperty"]);
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать файл PPSM только для чтения через .NET" %}}
Используя API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), вы можете еще больше расширить возможности своего приложения для преобразования. Одной из функций может быть создание выходного файла только для чтения для повышения безопасности. API позволяет настроить файл PPSM только для чтения, что означает, что пользователи (после того, как они откроют презентацию) увидят рекомендацию только для чтения. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.ppsm", SaveFormat.Ppsm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-pot/" name="XSLFO в POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-ppsx/" name="XSLFO в PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-swf/" name="XSLFO в SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-powerpoint/" name="XSLFO в POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-otp/" name="XSLFO в OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-potm/" name="XSLFO в POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-ppt/" name="XSLFO в PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-pps/" name="XSLFO в PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-potx/" name="XSLFO в POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-xaml/" name="XSLFO в XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-ppsm/" name="XSLFO в PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/xslfo-to-pptm/" name="XSLFO в PPTM" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}