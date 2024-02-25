---
title: Преобразование формата JSON в PPSM через Java
description: Разбор JSON в PPSM на Java без использования Microsoft PowerPoint
url_ignore: /ru/java/conversion/json-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: PPSM
otherformats: PPS POT POWERPOINT PPSM PPTM POTM PPSX OTP POTX PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование формата JSON в PPSM через Java" h2="Java API для преобразования формата JSON в PPSM без использования Microsoft<sup>&reg;</sup> PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Используя [Aspose.Total для Java](https://products.aspose.com/total/java/), вы можете преобразовать формат JSON в PPSM в любом приложении Java за два простых шага. Во-первых, с помощью [Aspose.Cells for Java](https://products.aspose.com/cells/java/) вы можете преобразовать JSON в PPTX. После этого, используя [Aspose.Slides for Java](https://products.aspose.com/slides/java/), вы можете конвертировать PPTX в PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование формата JSON в PPSM через Java" %}}
1. Создайте новый объект [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) и откройте файл JSON.
2. Сохраните JSON как PPTX, используя [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) метод
3. Загрузите документ PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation).
4. Сохраните документ в формате PPSM, используя метод [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://releases.aspose.com/total/java/). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "convert-json-to-powerpoint.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
Кроме того, API позволяет анализировать JSON в PPSM с указанными параметрами макета. Чтобы указать параметры макета, вы можете использовать класс [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayoutoptions). Он позволяет обрабатывать массив как таблицу, игнорировать нули, игнорировать заголовок массива, игнорировать заголовок объекта, преобразовывать строку в число или дату, устанавливать формат даты и числа и устанавливать стиль заголовка. Все эти параметры позволяют вам представить ваши данные в соответствии с вашими потребностями. В следующем фрагменте кода показано, как установить параметры макета.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "set-layout-and-parse-json-to-powerpoint.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Установить макет и преобразовать формат JSON в PPSM через Java" %}}
Используя API, вы также можете конвертировать JSON в PPSM с водяным знаком. Чтобы добавить водяной знак в документ PPSM, вы можете сначала преобразовать JSON в PPTX и добавить к нему водяной знак. Чтобы добавить водяной знак, загрузите только что созданный файл PPTX с помощью класса [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation), просмотрите все слайды, добавьте текст используя addTextFrame, установите все соответствующие параметры, такие как цвет, fillType и другие, и можете сохранить документ в PPSM. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d08aadfe6b1e1405bd50bc955df6183d" "parse-json-to-powerpoint-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}