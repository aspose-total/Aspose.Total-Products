---
title: Экспорт MD в ODP через C# API
description: .NET API для преобразования MD в ODP без использования Microsoft Word
url_ignore: /ru/net/conversion/md-to-odp/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: ODP
otherformats: XAML SWF POT PPTM PPSX POTM PPS PPT POTX OTP POWERPOINT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг MD в ODP через .NET" h2=".NET API для экспорта MD в ODP в Windows, macOS и Linux без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя пакет мощных API-интерфейсов автоматизации форматов файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко преобразовать MD в ODP, выполнив два простых шага. Используя API обработки PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файла MD в PPTX. После этого с помощью API обработки презентаций [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) вы можете конвертировать PPTX в ODP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования MD в ODP" %}}
1. Откройте файл MD, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте MD в PPTX, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл PPTX с помощью класса [Презентация](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Сохраните документ в формате ODP с помощью метода [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) и установите «Odp» в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "convert-md-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить метаданные XMP из файла MD через .NET" %}}
При преобразовании MD в ODP вам может понадобиться дополнительная информация о метаданных XMP, чтобы определить приоритетность процесса пакетного преобразования. Например, вы можете получать и сортировать документы преобразования по дате создания и соответствующим образом обрабатывать документы. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) позволяет получить доступ к метаданным XMP файла MD. Чтобы получить метаданные файла MD, вы можете создать объект [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document) и открыть входной файл MD. После этого вы можете получить метаданные файла с помощью свойства [Метаданные](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7ecbbfdbaa20b684f7fe108b8da68d71" "decrypt-md-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать файл ODP только для чтения через .NET" %}}
Используя API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), вы можете еще больше расширить возможности своего приложения для преобразования. Одной из функций может быть создание выходного файла только для чтения для повышения безопасности. API позволяет настроить файл ODP только для чтения, что означает, что пользователи (после того, как они откроют презентацию) увидят рекомендацию только для чтения. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.odp", SaveFormat.Odp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла MD в ODP: примеры использования" %}}
Файлы MD (Markdown) предназначены для хранения текстового контента, делают их идеальным выбором для создания документации и контента. Однако при работе с требованиями дизайна и презентации форматы ODP (OpenDocument Presentation) становятся необходимостью для создания привлекательных слайд-шоу и презентаций.

Конвертация файлов MD в форматы ODP позволяет раскрыть полные возможности вашей визуальной способности и дизайна. Это делает возможным:

**Примеры использования:**

*   **Презентации на конференциях**: Создание привлекательных презентаций с использованием текста, изображений и многомедийного контента.
*   **Материалы обучения**: Использование форматов ODP для визуализации учебных материалов, таких как планы курсов, лекционные заметки и手боксы.
*   **Внутренние коммуникации**: Создание профессионального вида внутренних коммуникаций, включая обновления компании, политику и руководства сотрудников.
*   **Образовательные ресурсы**: Разработка визуально привлекательных образовательных ресурсов, таких как учебники и рабочие тетради.
*   **Маркетинговые материалы**: Создание привлекательных маркетинговых материалов, таких как буклеты и листlets продаж.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}