---
title: Экспорт CGM в PPTM через C# API
description: .NET API для преобразования CGM в PPTM без использования Microsoft Word
url_ignore: /ru/net/conversion/cgm-to-pptm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: PPTM
otherformats: POT OTP PPS POTX POWERPOINT XAML POTM PPT PPSM PPSX SWF PPTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг CGM в PPTM через .NET" h2=".NET API для экспорта CGM в PPTM в Windows, macOS и Linux без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя пакет мощных API-интерфейсов автоматизации форматов файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко преобразовать CGM в PPTM, выполнив два простых шага. Используя API обработки PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файла CGM в PPTX. После этого с помощью API обработки презентаций [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) вы можете конвертировать PPTX в PPTM.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования CGM в PPTM" %}}
1. Откройте файл CGM, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте CGM в PPTX, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл PPTX с помощью класса [Презентация](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Сохраните документ в формате PPTM с помощью метода [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) и установите «Pptm» в качестве SaveFormat.
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
При преобразовании CGM в PPTM вам может понадобиться дополнительная информация о метаданных XMP, чтобы определить приоритетность процесса пакетного преобразования. Например, вы можете получать и сортировать документы преобразования по дате создания и соответствующим образом обрабатывать документы. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) позволяет получить доступ к метаданным XMP файла CGM. Чтобы получить метаданные файла CGM, вы можете создать объект [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document) и открыть входной файл CGM. После этого вы можете получить метаданные файла с помощью свойства [Метаданные](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать файл PPTM только для чтения через .NET" %}}
Используя API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), вы можете еще больше расширить возможности своего приложения для преобразования. Одной из функций может быть создание выходного файла только для чтения для повышения безопасности. API позволяет настроить файл PPTM только для чтения, что означает, что пользователи (после того, как они откроют презентацию) увидят рекомендацию только для чтения. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.pptm", SaveFormat.Pptm);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла CGM в PPTM: примеры использования" %}}
Переведение файлов CGM (Computer Graphics Metafile) в форматы PPTM (Microsoft PowerPoint Macro-Enabled Template) необходимо для раскрытия полной потенциальной возможностей вашей возможностей визуализации и анализа презентаций. Это преобразование позволяет вам:

**Примеры использования:**

*   **Разработка презентаций**: Перевести файлы CGM в формат PPTM для создания привлекательных презентаций, анимаций и интерактивов, что делает их идеальным для корпоративного обучения, материалов для маркетинга и pitches на продажах.  
*   **Создание инфографики**: Использовать формат PPTM для разработки и визуализации данных-драйвенных инфографиков, подчёркивая ключевые тенденции и выводы в краткой и убедительной форме.  
*   **Интерактивное повествование**: Перевести файлы CGM в формат PPTM для создания иммерсивных презентаций, которые включают элементы масс-медиа, такие как аудио, видео и анимации, чтобы зачаровать аудиторию и передать сложную информацию в интересный и привлекательный способ.  
*   **Отчетность бизнес-аналитики**: Использовать формат PPTM для визуализации данных бизнеса, отслеживания ключевых показателей производительности (КПИ) и выявления тенденций, что позволяет принимать более обоснованные решения и планировать стратегические действия.  
*   **Разработка курсов электронного обучения**: Перевести файлы CGM в формат PPTM для создания интерактивных модулей обучения, симуляций и игр, что повышает усвоение знаний, вовлекает студентов и улучшает общее качество обучения.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}