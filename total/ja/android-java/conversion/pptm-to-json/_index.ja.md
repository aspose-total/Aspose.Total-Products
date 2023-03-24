---
title: Javaを介してAndroidでPPTMをJSONに変換する
description: Microsoft ExcelまたはPowerPointを使用せずに、Javaを介してAndroidでPPTMをJSONに変換する

family: total
platformtag: cpp
feature: conversion
informat: PPTM
outformat: JSON
otherformats: DOC DOCM DOCX DOT DOTM DOTX ODT OTT RTF TEXT WORD WORDML
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Javaを介してAndroidでPPTMをJSONに変換する" h2="Microsoft <sup>＆reg; </sup>ExcelまたはPowerPointを使用せずにAndroidアプリケーションでPPTMファイルをJSONにエクスポートする" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Android via Java](https://products.aspose.com/total/android-java/)を使用すると、AndroidアプリケーションでPPTMファイルをJSONに簡単に変換できます。最初のステップでは、[Aspose.Slides for Android via Java](https://products.aspose.com/slides/android-java/)を使用してPPTMファイルをHTMLにエクスポートできます。次に、[Aspose.Cells for Android via Java](https://products.aspose.com/cells/android-java/)を使用すると、HTMLをJSONに変換できます。 
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="AndroidでPPTMをJSONに変換する方法" %}}
1. [プレゼンテーション](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTMファイルを開きます
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slides)を使用してPPTMをHTMLに変換します。ISaveOptions-)メソッド
3. [ワークブック](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)クラスを使用してHTMLドキュメントをロードします
4. [Save](https://reference.aspose.com/cells/java/com.aspose.cells/)を使用してドキュメントをJSON形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
PPTMをJSONに変換するには、[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com)から直接Java経由でAspose.TotalforAndroidを簡単に使用できます。 / aspose / aspose-total)そしてアプリにライブラリをインストールします。

または、[ダウンロード](https://releases.aspose.com/total/androidjava)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json.java" >}}



{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Javaを介してAndroidで保護されたPPTMをJSONに変換する" %}}
APIを使用して、パスワードで保護されたドキュメントを開くこともできます。入力PPTMドキュメントがパスワードで保護されている場合、パスワードを使用せずにJSONに変換することはできません。 APIを使用すると、LoadOptionsオブジェクトに正しいパスワードを渡すことで、暗号化されたドキュメントを開くことができます。次のコード例は、パスワードを使用して暗号化されたドキュメントを開こうとする方法を示しています。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-protected-powerpoint-to-json.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Androidで透かしを使用してPPTMファイルをJSONに変換する" %}}
PPTMファイルをJSONに変換するときに、出力JSONファイル形式に透かしを追加することもできます。透かしを追加するには、新しいワークブックを作成して、変換されたHTMLファイルを開きます。インデックスからワークシートを選択し、シェイプを作成してaddTextEffect関数を使用し、色や透明度などを設定します。その後、透かしを使用してHTMLドキュメントをJSONとして保存できます。
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "de2e3326ba6b04e5bcfea349e873be2b" "convert-powerpoint-to-json-range.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}