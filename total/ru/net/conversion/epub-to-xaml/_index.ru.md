---
title: Экспорт EPUB в XAML через C# API
description: .NET API для преобразования EPUB в XAML без использования Microsoft Word
url_ignore: /ru/net/conversion/epub-to-xaml/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: XAML
otherformats: PPTM OTP SWF PPSX PPS POWERPOINT XAML POTM PPSM PPT POTX POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг EPUB в XAML через .NET" h2=".NET API для экспорта EPUB в XAML в Windows, macOS и Linux без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя пакет мощных API-интерфейсов автоматизации форматов файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко преобразовать EPUB в XAML, выполнив два простых шага. Используя API обработки PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файла EPUB в PPTX. После этого с помощью API обработки презентаций [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) вы можете конвертировать PPTX в XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования EPUB в XAML" %}}
1. Откройте файл EPUB, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте EPUB в PPTX, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл PPTX с помощью класса [Презентация](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Сохраните документ в формате XAML с помощью метода [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) и установите «Xaml» в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить метаданные XMP из файла EPUB через .NET" %}}
При преобразовании EPUB в XAML вам может понадобиться дополнительная информация о метаданных XMP, чтобы определить приоритетность процесса пакетного преобразования. Например, вы можете получать и сортировать документы преобразования по дате создания и соответствующим образом обрабатывать документы. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) позволяет получить доступ к метаданным XMP файла EPUB. Чтобы получить метаданные файла EPUB, вы можете создать объект [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document) и открыть входной файл EPUB. После этого вы можете получить метаданные файла с помощью свойства [Метаданные](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EPUB в XAML: примеры использования" %}}
Перевёртывание файлов EPUB в форматы XAML открывает потенциал ваших визуализаций и возможностей анализа. 

Эта конверсия позволяет:

**Используемые примеры:**

*   **Разработка динамических интерфейсов пользователя**: Перевёртывание файлов EPUB в форматы XAML помогает создавать интерактивные и динамические интерфейсы для мобильных приложений, обеспечивая плавную навигацию и интересные пользователю опыт.
*   **Разработка контента для обучения**: Используйте форматы XAML для создания привлекательного контента для обучения, включая интерактивные симуляции, тесты и оценки, что способствует повышению усвоения знаний и развития навыков.
*   **Анализ изображений медицинского типа**: Перевёртывание файлов EPUB в форматы XAML позволяет визуализировать данные из изображений медицинского назначения, таких как МРТ и КТ, что упрощает диагностику и планирование лечения.
*   **Визуализация геоспациальных данных**: Используйте форматы XAML для создания интерактивных визуализаций геоспациальной информации, включая карты, спутниковую съемку и 3D-модели, что способствует лучшему пониманию сложных геоспациальных данных.
*   **Создание историй на основе данных**: Перевёртывание файлов EPUB в форматы XAML позволяет создавать истории на основе данных, включая интерактивные графики, диаграммы и инфографики, что увеличивает заинтересованность аудитории и понимание информации.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}