---
title: Java経由でPPTMをTEXTに変換する
description: MicrosoftWordやPowerPointを使用せずにPPTMをTEXTにエクスポートするJavaAPI
url_ignore: /ja/java/conversion/pptm-to-text/
family: total
platformtag: net
feature: conversion
informat: PPTM
outformat: TEXT
otherformats: DOTM TEXTM RTF WORDML DOTX TEXTX TEXT FLATOPC WORD DOT OTT ODT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java経由でPPTMをTEXTに変換する" h2="任意のJavaJ2SE、J2EE、J2MEアプリケーション内でのPowerPointPPTMからTEXTへの変換のためのオンプレミスJavaAPI" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/)ファイル形式自動化ライブラリにより、Java開発者はPowerPointPPTMからWordTEXTへのバッチ変換プロセスを自動化できます。ドキュメントの変換は2段階のプロセスであり、2つのAPIを使用する必要があります。 PPTMをHTMLに変換するためのプレゼンテーションの操作と管理のためのPowerPointAPIである[Aspose.Slides for Java](https://products.aspose.com/slides/java/)を使用します。その後、機能豊富なワードプロセッシングAPI [Aspose.Words for Java](https://products.aspose.com/words/java/)を使用して、HTMLをTEXTに変換します。
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Javaを介してPPTMをTEXTに変換する方法" %}}
1. [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)クラスを使用してPPTMファイルを開きます
2. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-com.aspose.slidesを使用してPPTMをHTMLに変換します。 ISaveOptions-)メソッドを使用し、HtmlをSaveFormatとして設定します
3. [Textument](https://reference.aspose.com/words/java/com.aspose.words/Textument)クラスを使用して変換されたHTMLファイルをロードします
4. [save](https://reference.aspose.com/words/java/com.aspose.words/Textument#save(java.lang.String,int))メソッドを使用してドキュメントをTEXT形式で保存します
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}
PPTMからTEXTファイルへの変換では、[Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose)から直接Aspose.TotalforJavaを簡単に使用できます。 / aspose-total)ベースのプロジェクトであり、pom.xmlにライブラリを含めます。

または、[ダウンロード](https://downloads.aspose.com/total/java)からZIPファイルを取得することもできます。
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="変換要件" %}}
APIを使用して、透かしを使用してPPTMファイルからTEXTへの変換を実行することもできます。 TEXTドキュメントに透かしを追加するには、最初にPPTMファイルをHTMLに変換し、それに透かしを追加します。透かしを追加するには、[Textument](https://reference.aspose.com/words/java/com.aspose.words/Textument)クラスを使用して新しく作成したHTMLファイルをロードし、TextWatermarkOptionsのインスタンスを作成して設定します。そのプロパティ、Watermark.setTextメソッドを呼び出し、TextWatermarkOptionsの透かしテキストとオブジェクトを渡します。  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "e2391d73d26866486249478b88c2ad59" "convert-powerpoint-to-word-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="その他の変換オプション" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-word/" name="PPTM に WORD" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-dotx/" name="PPTM に DOTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-odt/" name="PPTM に ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-ott/" name="PPTM に OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-rtf/" name="PPTM に RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-flatopc/" name="PPTM に FLAにPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-wordml/" name="PPTM に WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-textm/" name="PPTM に TEXTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-text/" name="PPTM に TEXT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-textx/" name="PPTM に TEXTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-dotm/" name="PPTM に DOTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ja/net/conversion/pptm-to-dot/" name="PPTM に DOT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}