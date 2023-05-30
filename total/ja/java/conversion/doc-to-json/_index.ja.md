---
title: Javaを介してDOCをJSON形式に変換する
description: MicrosoftWordまたはMicrosoftExcelを使用せずに、Javaを介してDOCをJSON形式に変換します
url_ignore: /ja/java/conversion/doc-to-json/
family: total
platformtag: net
feature: conversion
informat: DOC
outformat: JSON
otherformats: XLAM XLT CSV XLSX FODS XLTM XLSM XLTX ODS XLSB EXCEL SXC TSV DIF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Javaを介してDOCをJSON形式に変換する" h2="オンプレミスのJavaAPIを使用して、Microsoft<sup>＆reg;</sup>WordまたはMicrosoft<sup>＆reg; </sup>Excelを使用せずにDOCをJSONに変換する" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)を介してDOCをJSON形式に変換するのは、単純な2ステップのプロセスです。機能豊富なドキュメント操作および変換API[Aspose.Wordsfor Java](https://products.aspose.com/words/java/)を使用することにより、DOCをHTMLにエクスポートできます。その後、[Aspose.Cells for Java](https://products.aspose.com/cells/java/)を使用して、HTMLをJSONに変換できます。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してDOCをJSON形式に変換する" %}}
1. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)クラスを使用してDOCファイルを開きます
2. [Save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)を使用してDOCをHTMLに変換します) 方法
3. [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してHTMLドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells))を使用して、ドキュメントをJSON形式で保存します。 SaveOptions))メソッド
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
[Maven](https://releases.aspose.com/total/java/)ベースのプロジェクトから直接Aspose.Total for Javaを簡単に使用できますそして、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://releases.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
APIを使用して、パスワードで保護されたドキュメントを開くこともできます。入力DOCドキュメントがパスワードで保護されている場合、パスワードを使用せずにJSON形式に変換することはできません。 APIを使用すると、LoadOptionsオブジェクトで正しいパスワードを渡すことにより、暗号化されたドキュメントを開くことができます。次のコード例は、パスワードを使用して暗号化されたドキュメントを開こうとする方法を示しています。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-protected-word-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="保護されたDOCをJava経由でJSON形式に変換する" %}}
DOCをJSONに変換しているときに、範囲を出力JSON形式に設定することもできます。範囲を設定するには、Workbookクラスを使用して変換されたHTMLを開き、Cells.createRangeメソッドを使用してエクスポートするデータの範囲を作成し、RangeおよびExportRangeToJsonOptionsを参照してJsonUtility.exportRangeToJsonメソッドを呼び出し、文字列JSONデータをファイルに書き込みます。 BufferedWriter.writeメソッド。 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "aa0de5f99dc2a07e32a776a548eac3fa" "convert-word-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}