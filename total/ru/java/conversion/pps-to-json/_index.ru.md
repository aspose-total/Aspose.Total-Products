---
title: Преобразование PPS в формат JSON через Java
description: Преобразование PPS в формат JSON через Java без использования Microsoft Excel или PowerPoint
url: /ru/java/conversion/pps-to-json/
family: total
platformtag: net
feature: conversion
informat: PPS
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование PPS в формат JSON через Java" h2="Локальный Java API для экспорта PPS в JSON без использования Microsoft<sup>&reg;</sup> Excel или PowerPoint" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование PPS в формат JSON с помощью [Aspose.Total для Java](https://products.aspose.com/total/java/) — это простой двухэтапный процесс. На первом этапе вы можете экспортировать PPS в HTML, используя [Aspose.Slides for Java](https://products.aspose.com/slides/java/). Во-вторых, с помощью [Aspose.Cells for Java](https://products.aspose.com/cells/java/) вы можете конвертировать HTML в JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование PPS в формат JSON через Java" %}}
1. Откройте файл PPS с помощью класса [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation).
2. Преобразуйте PPS в HTML, используя [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides. ISaveOptions-) метод
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
С помощью API вы также можете открыть защищенный паролем документ. Если ваш входной PPS-документ защищен паролем, вы не сможете преобразовать его в формат JSON без использования пароля. API позволяет открыть зашифрованный документ, указав правильный пароль в объекте LoadOptions.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного PPS в формат JSON через Java" %}}
Пока вы конвертируете PPS в JSON, вы также можете установить диапазон выходного формата JSON. Чтобы установить диапазон, вы можете открыть преобразованный HTML с помощью класса Workbook, создать диапазон данных для экспорта с помощью метода Cells.createRange, вызвать метод JsonUtility.exportRangeToJson со ссылками Range и ExportRangeToJsonOptions и записать строковые данные JSON в файл через Метод BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-doc/" name="PPS К DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-docm/" name="PPS К DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-docx/" name="PPS К DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-dot/" name="PPS К DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-dotm/" name="PPS К DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-dotx/" name="PPS К DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-odt/" name="PPS К ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-ott/" name="PPS К OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-rtf/" name="PPS К RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-text/" name="PPS К TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-word/" name="PPS К WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/pps-to-wordml/" name="PPS К WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}