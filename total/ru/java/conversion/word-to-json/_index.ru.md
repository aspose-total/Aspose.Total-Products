---
title: Преобразование WORD в формат JSON через Java
description: Преобразование WORD в формат JSON через Java без использования Microsoft Word или Microsoft Excel
url_ignore: /ru/java/conversion/word-to-json/
family: total
platformtag: net
feature: conversion
informat: WORD
outformat: JSON
otherformats: SXC XLSX XLS DIF XLSB XLT XLAM TSV XLTM XLSM EXCEL XLTX FODS CSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Преобразование WORD в формат JSON через Java" h2="Локальный Java API для преобразования WORD в JSON без использования Microsoft<sup>&reg;</sup> Word или Microsoft<sup>&reg;</sup> Excel" >}}
{{% blocks/products/pf/feature-page-summary %}}
Преобразование WORD в формат JSON с помощью [Aspose.Total для Java](https://products.aspose.com/total/java/) — это простой двухэтапный процесс. Используя многофункциональный API для обработки и преобразования документов [Aspose.Words for Java](https://products.aspose.com/words/java/), вы можете экспортировать WORD в HTML. После этого с помощью [Aspose.Cells for Java](https://products.aspose.com/cells/java/) вы можете конвертировать HTML в JSON.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование WORD в формат JSON через Java" %}}
1. Откройте файл WORD, используя класс [Document](https://reference.aspose.com/words/java/com.aspose.words/Document).
2. Преобразуйте WORD в HTML, используя [Сохранить](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions) ) метод
3. Загрузите HTML-документ с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате JSON с помощью [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total для Java непосредственно из проекта на основе [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total). и включите библиотеки в свой pom.xml.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Требования к конвертации" %}}
С помощью API вы также можете открыть защищенный паролем документ. Если ваш входной документ WORD защищен паролем, вы не сможете преобразовать его в формат JSON без использования пароля. API позволяет открыть зашифрованный документ, указав правильный пароль в объекте LoadOptions. В следующем примере кода показано, как попытаться открыть зашифрованный документ с помощью пароля:  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного WORD в формат JSON через Java" %}}
Пока вы конвертируете WORD в JSON, вы также можете установить диапазон выходного формата JSON. Чтобы установить диапазон, вы можете открыть преобразованный HTML с помощью класса Workbook, создать диапазон данных для экспорта с помощью метода Cells.createRange, вызвать метод JsonUtility.exportRangeToJson со ссылками Range и ExportRangeToJsonOptions и записать строковые данные JSON в файл через Метод BufferedWriter.write. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Другие варианты преобразования" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xlam/" name="WORD К XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xlt/" name="WORD К XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-csv/" name="WORD К CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xlsx/" name="WORD К XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-fods/" name="WORD К FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xltm/" name="WORD К XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xlsm/" name="WORD К XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xltx/" name="WORD К XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-ods/" name="WORD К ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-xlsb/" name="WORD К XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-excel/" name="WORD К EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-sxc/" name="WORD К SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-tsv/" name="WORD К TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ru/net/conversion/word-to-dif/" name="WORD К DIF" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}