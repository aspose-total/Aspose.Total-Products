---
title: Java経由でPPSXをFLATOPCに変換する
description: MicrosoftWordやPowerPointを使用せずにPPSXをFLATOPCにエクスポートするJavaAPI
url_ignore: /ja/java/conversion/ppsx-to-flatopc/
family: total
platformtag: net
feature: conversion
informat: PPSX
outformat: FLATOPC
otherformats: TEXT FLATOPCX WORD WORDML FLATOPCM OTT FLATOPC DOT RTF ODT DOTX DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でPPSXをFLATOPCに変換する" h2="任意のJavaJ2SE、J2EE、J2MEアプリケーション内でのPowerPointPPSXからFLATOPCへの変換のためのオンプレミスJavaAPI" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)ファイル形式自動化ライブラリにより、Java開発者はPowerPointPPSXからWordFLATOPCへのバッチ変換プロセスを自動化できます。ドキュメントの変換は2段階のプロセスであり、2つのAPIを使用する必要があります。 PPSXをHTMLに変換するためのプレゼンテーションの操作と管理のためのPowerPointAPIである[Aspose.Slides for Java](https://products.aspose.com/slides/java/)を使用します。その後、機能豊富なワードプロセッシングAPI [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用して、HTMLをFLATOPCに変換します。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してPPSXをFLATOPCに変換する方法" %}}
1. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPSXファイルを開きます
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesを使用してPPSXをHTMLに変換します。 ISaveOptions-)メソッドを使用し、HtmlをSaveFormatとして設定します
3. [Flatopcument](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument)クラスを使用して変換されたHTMLファイルをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument#save(java.lang.String,int))メソッドを使用してドキュメントをFLATOPC形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
PPSXからFLATOPCファイルへの変換では、[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose)から直接Aspose.TotalforJavaを簡単に使用できます。 / aspose-total)ベースのプロジェクトであり、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://downloads.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
APIを使用して、透かしを使用してPPSXファイルからFLATOPCへの変換を実行することもできます。 FLATOPCドキュメントに透かしを追加するには、最初にPPSXファイルをHTMLに変換し、それに透かしを追加します。透かしを追加するには、[Flatopcument](https://reference.aspose.com/words/java/com.aspose.words/Flatopcument)クラスを使用して新しく作成したHTMLファイルをロードし、TextWatermarkOptionsのインスタンスを作成して設定します。そのプロパティ、Watermark.setTextメソッドを呼び出し、TextWatermarkOptionsの透かしテキストとオブジェクトを渡します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-word/" name="PPSX に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-dotx/" name="PPSX に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-odt/" name="PPSX に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-ott/" name="PPSX に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-rtf/" name="PPSX に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-flatopc/" name="PPSX に FLAにPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-wordml/" name="PPSX に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-flatopcm/" name="PPSX に FLATOPCM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-text/" name="PPSX に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-flatopcx/" name="PPSX に FLATOPCX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-dotm/" name="PPSX に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/ppsx-to-dot/" name="PPSX に DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}