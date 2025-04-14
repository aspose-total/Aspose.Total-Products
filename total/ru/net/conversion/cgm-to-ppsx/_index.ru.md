---
title: Экспорт CGM в PPSX через C# API
description: .NET API для преобразования CGM в PPSX без использования Microsoft Word
url_ignore: /ru/net/conversion/cgm-to-ppsx/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPSX
otherformats: PPT POWERPOINT POTX POTM PPS SWF PPSM PPTM XAML OTP POT PPSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг CGM в PPSX через .NET" h2=".NET API для экспорта CGM в PPSX в Windows, macOS и Linux без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя пакет мощных API-интерфейсов автоматизации форматов файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко преобразовать CGM в PPSX, выполнив два простых шага. Используя API обработки PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файла CGM в PPTX. После этого с помощью API обработки презентаций [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) вы можете конвертировать PPTX в PPSX.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования CGM в PPSX" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте CGM в PPTX, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл PPTX с помощью класса [Презентация](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Сохраните документ в формате PPSX с помощью метода [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) и установите «Ppsx» в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить метаданные XMP из файла CGM через .NET" %}}
При преобразовании CGM в PPSX вам может понадобиться дополнительная информация о метаданных XMP, чтобы определить приоритетность процесса пакетного преобразования. Например, вы можете получать и сортировать документы преобразования по дате создания и соответствующим образом обрабатывать документы. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) позволяет получить доступ к метаданным XMP файла CGM. Чтобы получить метаданные файла CGM, вы можете создать объект [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document) и открыть входной файл CGM. После этого вы можете получить метаданные файла с помощью свойства [Метаданные](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
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

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла CGM в PPSX: примеры использования" %}}
Программирование файлов CGM (Computer Graphics Metafile) в формат PPSX (Microsoft PowerPoint XML Presentation File) позволяет раскрыть полную потенциал данных вашей презентации для визуализации и анализа. Эта конверсия необходима, чтобы использовать силу функций интерактивности PowerPoint, таких как анимации, переходы и содержание многомедийное.

Конверсия файлов CGM в форматы PPSX открывает различные случаи применения:

**Примеры использования:**

*   **Дизайн и разработка презентаций**: Преобразование файлов CGM в формат PPSX позволяет создавать привлекательные презентации, симуляции и интерактивные визуализации, которые привлекут внимание аудитории.
*   **Рассказываемое данные**: Использование формата PPSX позволяет внедрить сложные данные в презентации, позволяя вам эффективно передавать сообщение через рассказывание и визуализацию.
*   **Корпоративные коммуникации и отчеты**: Преобразование файлов CGM в формат PPSX позволяет создавать профессиональные отчеты, дашборды и визуализации для стейкхолдеров, что способствует обоснованному принятию решений.
*   **Кампании рекламирования и маркетинга**: Использование возможностей формата PPSX позволяет внедрить динамическое содержание, анимации и видео в презентации, усиливая сообщение о маркетинге и рекламе.
*   **Научные и исследовательские презентации**: Использование формата PPSX позволяет создавать профессиональные научные презентации, которые включают сложную визуализацию данных, симуляции и элементы многомедийного содержания.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}