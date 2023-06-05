---
title: Преобразование веб-страниц HTML в изображения с помощью C#
description: Очистите веб-страницы веб-сайта и экспортируйте HTML в изображения. Разрабатывайте приложения .NET для преобразования данных веб-сайта в форматы JPEG, PNG, GIF, BMP и т. д. 
family: total
platformtag: net
feature: conversion
informat: WEB
outformat: IMAGE
otherformats: WORD EXCEL POWERPOINT PDF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование веб-страниц в изображения с помощью C#" h2="Извлечение данных веб-сайта из веб-страниц HTML. Преобразование HTML в изображения JPG, GIF, PNG, BMP в приложениях .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}

<h2 class="heading-border">Зачем конвертировать веб-страницы в изображения?</h2>
<p>Преобразование веб-страниц в изображения может быть полезно в различных ситуациях. Это общее требование для многих приложений. В некоторых сценариях необходимо захватить всю веб-страницу как изображение, включая части, которые не видны на экране. Это может быть полезно для создания предварительных просмотров веб-сайтов, сбора квитанций и счетов-фактур или архивирования веб-страниц в юридических целях. Его можно использовать для создания скриншотов веб-страниц для документации или тестирования. Его также можно использовать для создания эскизов или предварительных просмотров веб-страниц для использования в результатах поиска или галереях изображений. Независимо от того, создаете ли вы настольное приложение или веб-приложение, существует множество вариантов преобразования веб-страниц в изображения с помощью C#.</p><br />

<p>Преобразование веб-страниц в изображения с помощью C# может дать несколько преимуществ, в том числе:</p><br />
<ul>
<li>Улучшенная доступность: Изображения могут быть проще для чтения и понимания людьми с нарушениями зрения или другими ограниченными возможностями.</li>
<li>Повышенная портативность: Изображениями можно легко поделиться или встроить в другие документы или приложения.</li>
</ul>
<p>Преобразование веб-страниц в изображения с помощью C# также может вызвать некоторые проблемы, в том числе:</p><br />
<ul>
<li>Ограниченная поддержка форматов: Некоторые API или инструменты могут поддерживать не все форматы изображений или иметь ограничения на размер или разрешение выходных изображений.</li>
<li>Проблемы совместимости: Некоторые веб-страницы могут отображаться некорректно во всех браузерах или могут требовать определенных настроек или подключаемых модулей для правильного отображения.</li>
</ul>
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Как конвертировать веб-страницы в изображения с помощью C#?" %}}
Чтобы преобразовать веб-страницы в изображения с помощью C#, вы можете использовать Aspose.HTML для .NET API, который предоставляет эту функциональность для преобразования HTML-страниц в форматы изображений, включая JPEG, PNG и TIFF.</p>

1. Загрузите документ HTML, используя один из конструкторов, доступных в [HTMLDocument()](https://reference.aspose.com/html/net/aspose.html/htmldocument/). Вы можете загрузить HTML из файла, HTML-кода, потока или URL-адреса.
2. Создайте новый экземпляр [ImageSaveOptions](https://reference.aspose.com/html/net/aspose.html.saving/imagesaveoptions/) и задайте для свойства ImageFormat значение JPEG. По умолчанию для свойства Формат установлено значение PNG.
3. Используйте [ConvertHTML()](https://reference.aspose.com/html/net/aspose.html.converters/converter/converthtml/) из класса Converter, чтобы сохранить HTML-документ в виде файла JPEG. Вам нужно будет указать HTMLDocument, ImageSaveOptions и путь к выходному файлу в качестве параметров метода ConvertHTML().
4. Полученный файл JPEG будет сохранен по указанному пути к файлу.
 
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к очистке веб-сайтов и преобразованию изображений" %}}
Установите из командной строки как «nuget install Aspose.Total» или установите непосредственно из консоли диспетчера пакетов Visual Studio.

Два [Aspose.Total for .NET](https://products.aspose.com/total/net/) дочерний API, [Aspose.HTML for .NET](https://products.aspose.com/html/net/) будут интегрированы.

Кроме того, получите автономный установщик MSI или библиотеки DLL в ZIP-файле из [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "7c89a27cea5417369683e976a8fae326" "convert-web-pages-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}