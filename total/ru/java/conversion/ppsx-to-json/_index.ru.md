---
title: Преобразование PPSX в формат JSON через Java
description: Преобразование PPSX в формат JSON через Java без использования Microsoft Excel или PowerPoint
url: /ru/java/conversion/ppsx-to-json/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование PPSX в формат JSON через Java" h2="Локальный Java API для экспорта PPSX в JSON без использования Microsoft<sup>&reg;</sup> Excel или PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование PPSX в формат JSON с помощью [Aspose.Total для Java](https://products.aspose.com/total/java/) — это простой двухэтапный процесс. На первом этапе вы можете экспортировать PPSX в HTML, используя [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Во-вторых, с помощью [Aspose.Cells for Java](https://products.aspose.com/cells/java/) вы можете конвертировать HTML в JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование PPSX в формат JSON через Java" %}}
1. Откройте файл PPSX с помощью класса [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Преобразуйте PPSX в HTML, используя [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) метод
3. Загрузите HTML-документ с помощью класса [Workbook](https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате JSON, используя [save](https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells. SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
С помощью API вы также можете открыть защищенный паролем документ. Если ваш входной PPSX-документ защищен паролем, вы не сможете преобразовать его в формат JSON без использования пароля. API позволяет открыть зашифрованный документ, указав правильный пароль в объекте LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного PPSX в формат JSON через Java" %}}
Пока вы конвертируете PPSX в JSON, вы также можете установить диапазон выходного формата JSON. Чтобы установить диапазон, вы можете открыть преобразованный HTML с помощью класса Workbook, создать диапазон данных для экспорта с помощью метода Cells.createRange, вызвать метод JsonUtility.exportRangeToJson со ссылками Range и ExportRangeToJsonOptions и записать строковые данные JSON в файл через Метод BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-doc/" name="PPSX К DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-docm/" name="PPSX К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-docx/" name="PPSX К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-dot/" name="PPSX К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-dotm/" name="PPSX К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-dotx/" name="PPSX К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-odt/" name="PPSX К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-ott/" name="PPSX К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-rtf/" name="PPSX К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-text/" name="PPSX К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-word/" name="PPSX К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/ppsx-to-wordml/" name="PPSX К WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}