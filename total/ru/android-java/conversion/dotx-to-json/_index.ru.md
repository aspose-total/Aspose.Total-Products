---
title: Преобразование DOTX в формат JSON в Android через Java
description: Преобразование DOTX в формат JSON в Android через Java без использования Microsoft Word или Excel

family: total
platformtag: cpp
feature: conversion
informat: DOTX
outformat: JSON
otherformats: SXC XLSM XLSB TSV XLAM XLT DIF EXCEL XLTX CSV XLTM FODS ODS XLSX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Преобразование DOTX в формат JSON в Android через Java" h2="Создавайте приложения Android для экспорта DOTX в JSON без использования Microsoft<sup>&reg;</sup> Word или Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}
Вы можете конвертировать DOTX в формат JSON в своих приложениях для Android через [Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/). Используя API для обработки и преобразования документов [Aspose.Words for Android via Java](https://products.aspose.com/words/android-java/), вы можете экспортировать DOTX в HTML. После этого, используя [Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/), вы можете конвертировать HTML в JSON. 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Преобразование DOTX в формат JSON в Android" %}}
1. Откройте файл DOTX, используя класс [Dotxument](https://reference.aspose.com/words/java/com.aspose.words/Dotxument).
2. Преобразуйте DOTX в HTML, используя [Save](https://reference.aspose.com/words/java/com.aspose.words/Dotxument#save(java.lang.String,com.aspose.words.SaveOptions) ) метод
3. Загрузите HTML-документ с помощью класса [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook).
4. Сохраните документ в формате JSON с помощью [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) метод
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Требования к конвертации" %}}
Вы можете легко использовать Aspose.Total for Android via Java непосредственно из [Maven](https://releases.aspose.com/total/java/) и установить библиотеки в ваше приложение.

Кроме того, вы можете получить ZIP-файл из [загрузки](https://releases.aspose.comtotal/androidjava).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование защищенного DOTX в формат JSON в Android через Java" %}}
С помощью API вы также можете открыть защищенный паролем документ. Если ваш входной документ DOTX защищен паролем, вы не сможете преобразовать его в формат JSON без использования пароля. API позволяет открыть зашифрованный документ, указав правильный пароль в объекте LoadOptions. В следующем примере кода показано, как открыть зашифрованный документ с помощью пароля.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Преобразование DOTX в JSON в диапазоне в Android через Java" %}}
Пока вы конвертируете DOTX в JSON, вы также можете установить диапазон выходного формата JSON. Чтобы установить диапазон, вы можете открыть преобразованный HTML с помощью класса Workbook, создать диапазон данных для экспорта с помощью метода Cells.createRange, вызвать метод JsonUtility.exportRangeToJson со ссылками Range и ExportRangeToJsonOptions и записать строковые данные JSON в файл через Метод BufferedWriter.write.
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}