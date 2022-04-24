---
title: Преобразование формата JSON в EMZ через Java
description: Разбор JSON в EMZ на Java без использования Microsoft PowerPoint
url: /ru/java/conversion/json-to-emz/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: EMZ
otherformats: EMZ SVGZ DXF JPEG2000 PSD WMF WMZ TGA DICOM IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование формата JSON в EMZ через Java" h2="API Java для преобразования формата JSON в EMZ в любых приложениях Java J2SE, J2EE, J2ME." >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете преобразовать формат JSON в EMZ в любом приложении Java за два простых шага. Во-первых, с помощью [Aspose.Cells for Java](https://products.aspose.com/cells/java/) вы можете преобразовать JSON в JPEG. После этого с помощью [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/) вы можете конвертировать JPEG в EMZ.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в EMZ через Java" %}}
1. Создайте новый объект [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook) и откройте файл JSON.
2. Сохраните JSON как JPEG, используя [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) метод
3. Загрузите документ JPEG с помощью класса [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image).
4. Сохраните документ в формате EMZ, используя [save](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase -) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки] (https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Кроме того, API позволяет вам преобразовывать JSON в EMZ с указанными параметрами макета. Чтобы указать параметры макета, вы можете использовать класс [JsonLayoutOptions](https://apireference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в EMZ через Java" %}}
Используя API, вы также можете конвертировать JSON в EMZ с водяным знаком в документе EMZ. Чтобы добавить водяной знак, вы можете сначала преобразовать JSON в JPEG и добавить в него водяной знак. Чтобы добавить водяной знак, загрузите файл изображения с помощью класса [Image](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Image), создайте объект класса [Graphics](https ://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics) и инициализируйте его с помощью объекта Image, создайте новую [Matrix] (https://apireference.aspose.com/imaging/java/ com.aspose.imaging/Matrix) и задайте перевод и трансформацию под желаемым углом и добавьте водяной знак с помощью [Graphics.drawString](https://apireference.aspose.com/imaging/java/com.aspose.imaging/Graphics# Метод drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). После добавления водяного знака на изображение вы можете сохранить JPEG в формате EMZ. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-jpeg2000/" name="JSON К JPEG2000" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-emz/" name="JSON К EMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-psd/" name="JSON К PSD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-wmf/" name="JSON К WMF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-wmz/" name="JSON К WMZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-dxf/" name="JSON К DXF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-image/" name="JSON К IMAGE" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-svgz/" name="JSON К SVGZ" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-dicom/" name="JSON К DICOM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/json-to-tga/" name="JSON К TGA" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}