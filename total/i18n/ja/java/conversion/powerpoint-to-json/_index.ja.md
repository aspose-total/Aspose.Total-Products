---
title: Javaを介してPOWERPOINTをJSON形式に変換する
description: Microsoft ExcelまたはPowerPointを使用せずに、Javaを介してPOWERPOINTをJSON形式に変換します
url: /ja/java/conversion/powerpoint-to-json/
family: total
platformtag: net
feature: conversion
informat: PPT
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してPOWERPOINTをJSON形式に変換する" h2="オンプレミスのJavaAPIで、Microsoft <sup>＆reg; </sup>ExcelまたはPowerPointを使用せずにPOWERPOINTをJSONにエクスポートする" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java]（https://products.aspose.com/total/java/）を介してPOWERPOINTをJSON形式に変換するのは、単純な2ステップのプロセスです。最初のステップでは、[Aspose.Slides for Java]（https://products.aspose.com/slides/java/）を使用してPOWERPOINTをHTMLにエクスポートできます。次に、[Aspose.Cells for Java]（https://products.aspose.com/cells/java/）を使用して、HTMLをJSONに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してPOWERPOINTをJSON形式に変換する" %}}
1. [プレゼンテーション]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation）クラスを使用してPOWERPOINTファイルを開きます
2. [save]（https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesを使用してPOWERPOINTをHTMLに変換します。 ISaveOptions-）メソッド
3. [Workbook]（https://apireference.aspose.com/cells/java/com.aspose.cells/Workbook）クラスを使用してHTMLドキュメントをロードします
4. [save]（https://apireference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells）を使用して、ドキュメントをJSON形式で保存します。 SaveOptions））メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven]（https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total）ベースのプロジェクトから直接Aspose.TotalforJavaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード]（https://downloads.aspose.com/total/java）からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
APIを使用して、パスワードで保護されたドキュメントを開くこともできます。入力POWERPOINTドキュメントがパスワードで保護されている場合、パスワードを使用せずにJSON形式に変換することはできません。 APIを使用すると、LoadOptionsオブジェクトで正しいパスワードを渡すことにより、暗号化されたドキュメントを開くことができます。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="保護されたPOWERPOINTをJava経由でJSON形式に変換する" %}}
POWERPOINTをJSONに変換しているときに、範囲を出力JSON形式に設定することもできます。範囲を設定するには、Workbookクラスを使用して変換されたHTMLを開き、Cells.createRangeメソッドを使用してエクスポートするデータの範囲を作成し、RangeおよびExportRangeToJsonOptionsを参照してJsonUtility.exportRangeToJsonメソッドを呼び出し、文字列JSONデータをファイルに書き込みます。 BufferedWriter.writeメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-doc/" name="POWERPOINT に DOC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-docm/" name="POWERPOINT に DOCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-docx/" name="POWERPOINT に DOCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-dot/" name="POWERPOINT に DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-dotm/" name="POWERPOINT に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-dotx/" name="POWERPOINT に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-odt/" name="POWERPOINT に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-ott/" name="POWERPOINT に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-rtf/" name="POWERPOINT に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-text/" name="POWERPOINT に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-word/" name="POWERPOINT に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/powerpoint-to-wordml/" name="POWERPOINT に WORDML" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}