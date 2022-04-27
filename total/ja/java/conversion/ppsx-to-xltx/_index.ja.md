---
title: Javaを介してPPSXをXLTX形式に変換する
description: MicrosoftExcelまたはPowerPointを使用せずにJava経由でPPSXをXLTX形式に変換する
url: /ja/java/conversion/ppsx-to-xltx/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: XLTX
otherformats: XLSM DIF FODS MARKDOWN XLSB XLAM MHTML XLTM XLT XLS TSV ODS SXC EXCEL XLTX XLSX DOC DOCX DOCM DOT DOTM DOTX ODT OTT RTF WORD WORDML TEXT FLATOPX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でPPSXをXLTXに変換する" h2="オンプレミスのJavaAPIを使用して、Microsoft <sup>＆reg; </sup>ExcelまたはPowerPointを使用せずにPPSXをXLTXにエクスポートする" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java]（https://products.aspose.com/total/java/）を使用して、2つのステップでPPSXファイルをXLTXに変換できます。最初のステップでは、[Aspose.Slides for Java]（https://products.aspose.com/slides/java/）を使用してPPSXをHTMLにエクスポートできます。次に、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用して、HTMLをXLTXに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してPPSXをXLTXに変換する方法" %}}
1. [プレゼンテーション]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）クラスを使用してPPSXファイルを開きます
2. [save]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesを使用してPPSXをHTMLに変換します。 ISaveOptions-）メソッド
3. [Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）クラスを使用してHTMLドキュメントをロードします
4. [save]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells）を使用して、ドキュメントをXLTX形式で保存します。 SaveOptions））メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
PPSXをXLTXに変換するには、[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/）から直接Aspose.TotalforJavaを簡単に使用できます。 aspose / aspose-total）ベースのプロジェクトであり、pom.xmlにライブラリを含めます。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
APIを使用して、パスワードで保護されたドキュメントを開くこともできます。入力したPPSXドキュメントがパスワードで保護されている場合、パスワードを使用せずにXLTXに変換することはできません。 APIを使用すると、LoadOptionsオブジェクトで正しいパスワードを渡すことにより、暗号化されたドキュメントを開くことができます。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-protected-powerpoint-to-excel.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="保護されたPPSXをJava経由でXLTXに変換する" %}}
PPSXファイルをXLTXに変換するときに、出力XLTXファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックを作成して、変換されたHTMLファイルを開きます。インデックスからワークシートを選択し、図形を作成してそのaddTextEffect関数を使用し、色や透明度などを設定します。その後、透かしを使用してHTMLドキュメントをXLTXとして保存できます。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "4b527b3966d48e40c1b50136eebdbb6e" "convert-powerpoint-to-excel-with-watermark.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-fods/" name="PPSX に FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-xltm/" name="PPSX に XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-xlt/" name="PPSX に XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-xlam/" name="PPSX に XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-markdown/" name="PPSX に MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-excel/" name="PPSX に EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-mhtml/" name="PPSX に MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-xlsb/" name="PPSX に XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-ods/" name="PPSX に ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-sxc/" name="PPSX に SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-xls/" name="PPSX に XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-xltx/" name="PPSX に XLTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-xlsx/" name="PPSX に XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-tsv/" name="PPSX に TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-dif/" name="PPSX に DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-xlsm/" name="PPSX に XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-doc/" name="PPSX に DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-docx/" name="PPSX に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-docm/" name="PPSX に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-dot/" name="PPSX に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-dotm/" name="PPSX に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-dotx/" name="PPSX に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-odt/" name="PPSX に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-ott/" name="PPSX に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-rtf/" name="PPSX に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-word/" name="PPSX に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-wordml/" name="PPSX に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-text/" name="PPSX に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-flatopx/" name="PPSX に FLAにPX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}