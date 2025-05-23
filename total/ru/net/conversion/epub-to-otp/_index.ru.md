---
title: Экспорт EPUB в OTP через C# API
description: .NET API для преобразования EPUB в OTP без использования Microsoft Word
url_ignore: /ru/net/conversion/epub-to-otp/
family: total
platformtag: net
feature: conversion
informat: EPUB
outformat: OTP
otherformats: OTP PPSX PPSM POTM POWERPOINT PPS POTX XAML SWF PPT PPTM POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Рендеринг EPUB в OTP через .NET" h2=".NET API для экспорта EPUB в OTP в Windows, macOS и Linux без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Используя пакет мощных API-интерфейсов автоматизации форматов файлов [Aspose.Total for .NET](https://products.aspose.com/total/net/), вы можете легко преобразовать EPUB в OTP, выполнив два простых шага. Используя API обработки PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), вы можете преобразовать формат файла EPUB в PPTX. После этого с помощью API обработки презентаций [Aspose.Slides for .NET](https://products.aspose.com/slides/net/) вы можете конвертировать PPTX в OTP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title=".NET API для преобразования EPUB в OTP" %}}
1. Откройте файл EPUB, используя класс [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Преобразуйте EPUB в PPTX, используя метод [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5).
3. Загрузите файл PPTX с помощью класса [Презентация](https://reference.aspose.com/slides/net/aspose.slides/presentation).
4. Сохраните документ в формате OTP с помощью метода [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) и установите «Otp» в качестве SaveFormat.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требование преобразования" %}}
Установите из командной строки как ```nuget install Aspose.Total``` или через консоль диспетчера пакетов Visual Studio с помощью ```Install-Package Aspose.Total```.

Кроме того, вы можете получить автономный установщик MSI или библиотеки DLL в ZIP - файле из[загрузки](https://releases.aspose.comtotal/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "convert-epub-to-powerpoint.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Получить метаданные XMP из файла EPUB через .NET" %}}
При преобразовании EPUB в OTP вам может понадобиться дополнительная информация о метаданных XMP, чтобы определить приоритетность процесса пакетного преобразования. Например, вы можете получать и сортировать документы преобразования по дате создания и соответствующим образом обрабатывать документы. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) позволяет получить доступ к метаданным XMP файла EPUB. Чтобы получить метаданные файла EPUB, вы можете создать объект [Документ](https://reference.aspose.com/pdf/net/aspose.pdf/document) и открыть входной файл EPUB. После этого вы можете получить метаданные файла с помощью свойства [Метаданные](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0e51da16990d47103fac757919644478" "decrypt-epub-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Создать файл OTP только для чтения через .NET" %}}
Используя API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), вы можете еще больше расширить возможности своего приложения для преобразования. Одной из функций может быть создание выходного файла только для чтения для повышения безопасности. API позволяет настроить файл OTP только для чтения, что означает, что пользователи (после того, как они откроют презентацию) увидят рекомендацию только для чтения. 
{{% blocks/products/pf/feature-page-code %}}

```cs
Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.otp", SaveFormat.Otp);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Программное преобразование файла EPUB в OTP: примеры использования" %}}
Файлы формата E-book (Electronic Publication) используются для хранения цифрового контента, что делает их идеальным вариантом для создания динамических содержимостей и интерактивных опытов. Однако при работе с офлайн-данными текстовые файлы становятся необходимостью для долгосрочного хранения и архивирования цифрового контента.

Преобразование файлов формата E-book в текстовые файлы офлайн позволяет раскрыть полную функциональность возможностей вашего архива и библиотеки. Это преобразование позволяет:

**Использование случаев:**

*   **Дigital Preservation (Дигитализация и сохранение):** Преобразовать файлы формата E-book в постоянные архивы, чтобы обеспечить доступность цифрового контента во времени.
*   **Офлайн чтение и распределение:** Использовать текстовые файлы для распространения цифровного контента без зависимости от интернет-соединительности, что делает это идеальным вариантом для регионов с ограниченным доступом или в условиях отсутствия Wi-Fi.
*   **Управление библиотекой и организация:** Преобразовать файлы формата E-book в структурированные коллекции текстовых данных, что упрощает поиск, категоризацию и извлечение конкретной информации.
*   **Архивирование и восстановление цифрового контента:** Использовать текстовые файлы для хранения цифровых артефактов и восстановления поврежденного контента, обеспечивая сохранение ценной информации для будущих поколений.
*   **Создание и редактирование офлайн-контента:** Преобразовать файлы формата E-book в редактируемый контент без зависимости от интернет-соединительности, что делает это идеальным вариантом для авторов, писателей и издателей, которые работают в孤立ных условиях или с ограниченным доступом к онлайн-ресурсам.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}